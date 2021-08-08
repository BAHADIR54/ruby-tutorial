## Integer

* integerlar ruby deki tam sayıları ifade eder.
* bu yazida integerların kullanımlarini ve metotlarını göreceğiz.

<h3>ornekler:</h3>

```ruby
x = 1
y = 2
t = "1"
puts x + y
puts t + x
```
```ruby
3
no implicit conversion of Integer into String (TypeError)
#integerler kendi aralarinda islem yapabilirler ama stringlerle beraber matematiksel hesaplar yapamazlar.
#veri donusumu yaparak bu sorunu cozebiliriz.
```
```ruby
puts t.to_i + x
```
```ruby
2
#to_i ile stringin integer formatina cevirebiliriz.
```

<h3>integer methodlar:</h3>

* integerlarin bircok methodu vardir en kullanisli methodlarindan biraz ornekler verelim.


**to_s ve to_i:**

* to_s methodu integerlari string formatina cevirir.
* to_i methodu stringleri integer formatina cevirir.

```ruby
y = "2"
z = 1
puts y.to_i
puts z.to_s
```
```ruby
2#artik bu bir string degil integer
1#artik bu bir integer degil string
```
