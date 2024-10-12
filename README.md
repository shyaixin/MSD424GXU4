// 主程序入口，模拟一些操作  
const customer = new Customer('Alice', '123456789', '123 Main St');  
const tomato = new FarmProduct('Tomato', 2.5, true);  
const farmManagement = new FarmManagement();  
farmManagement.addProduct(tomato);  
const order = new Order([tomato]);  
customer.addOrder(order);  
  
console.log('Customer:', customer.getName);  
console.log('Total Amount:', order.getTotalAmount);
