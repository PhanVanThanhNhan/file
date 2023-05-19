Viết các hàm dùng lại ở nhiều components

//func validate Email: hàm xác định component là email
export function isEmail(email) {
  // eslint-disable-next-line no-useless-escape
  const regex = /^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/;
  return regex.test(email);
}