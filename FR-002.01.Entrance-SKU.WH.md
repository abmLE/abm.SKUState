##FR-002.01
> comments

###Алгоритм "Ввод товара в ассортимент" (только для новых SKU/WH)
1. _Если_ BUF > 0, _то_ Status = MTS
2. _Если_ BUF < 0, _то_ Status = NM и Buffer= 1.5*MOQ
3. _Иначе_ (Если BUF = 0 или не указан), _то_ Status = MTО и Buffer=0

####Блоксхема
![alt text](http://cs628027.vk.me/v628027613/f330/PoTg1_ZF4LA.jpg)
