# Socks-warehouse
API на Java Spring(boot), позволяющее производить учёт(приход, уход, наличие) носков на складе.

# Примеры запросов CURL
 - curl -X POST "http://localhost:8080/api/socks/income?color=red&cottonPart=30&quantity=10"
 - curl -X POST "http://localhost:8080/api/socks/outcome?color=red&cottonPart=30&quantity=10"
 - curl -X GET "http://localhost:8080/api/socks?color=Red&operation=moreThan&cottonPart=10"

# Схема БД
![image](https://user-images.githubusercontent.com/15357812/136683218-c5998f47-3456-47ab-aa4c-73b0f295b1aa.png)
