classDiagram
 direction LR
 class form1{
 -cheakin():void
 -cheaout():void
 -Save():void
 -Clear():void
}
 class Pay{
 -discountcode():void
 -pay():void
 -back():void
 }
 class codepay{
 -couponCode:string
 -minimumPice:double
 +creat(double min):void
 +getCoupon():void
 }
 class Buy{
 -totalPice:double
 +Bill(pay double,getmoney Double):void
 +payBill():double
  }
  Pay -- codepay
  Pay -- Buy
  
