
# 快卖专区 order-detail

## 1、 访问

   //m.zhuanzhuan.58.com/order/newdetail.htm?oid=${item.orderid}&type=${item.type}&exchange=${item.isExchange}

## 2、 接口(zzyp\ZZY-m-order\src\conf\api.conf.js)

   - a、获取订单详情
   
   getOrderDetail接口调取事例: 
   
   ``jsonp(apiUrl.getOrderDetail, {oid,type,exchange}, null, (err, json) =>{})``
   
   
   - b、发货
   
   sendGood接口调取事例: 
   
   ``jsonp(apiUrl.sendGood, {oid,expresscode,exprescompany}, null, (err, json) => {})``
   
   - c、拒绝
   
   rejectSale接口调取事例: 
   
   ``jsonp(apiUrl.rejectSale, {oid,num}, null, (err, json) =>{})``
   
