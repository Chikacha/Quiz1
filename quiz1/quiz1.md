1.

Fixnum是整數  Float是含有小數的數值

2.

第一個方式會使用到額外的記憶體來做字串的搬移

第二個方式則是直接編譯轉換為新字串

3.

Array利用索引值來存取儲存的資料

Hash利用key值來存取儲存的資料

4.
```ruby
arr.reject {|x| x.is_a?(string)}
```

5.
```ruby
arr.map! {|x| x += 2}
```
6.

結果都是[1, 2, 3]，但uniq會產生一個新陣列，uniq!會直接動原本的陣列

7.
```ruby
[1, 2, 3].shuffle.last
```
```ruby
[1, 2, 3].sample
```
8.true

9.

是用來Debug, 監控參數狀態的套件

先安裝好之後在最上面用require引用

然後在要監控的變數下面打上binding.pry

10.
```ruby
return var >= 5 ? "var is greater than or equal to 5" : "var is less than 5"
```
11.

(1)用hash rocket
```ruby
:Dio => "The World"
```
(2)直接用冒號
```ruby
Dio : "The World"
```