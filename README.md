# **HW_1**  
## **Создать запросы в Postman.**    
```  
Protocol: http  
IP: 162.55.220.72  
Port: 5005   
```   
1. EP_1  
Method: `GET`  
EndPoint: `/get_method`  
request url params:   
name: `Aleksei`  
age: `33`   
```json  
[
    "Aleksei",
    "33"
]  
```

1. EP_2  
Method: `POST`   
EndPoint: `/user_info_3`  
request form data:   
name: `Aleksei`  
age: `33`  
salary: `800`  
```json
{
    "age": "33",
    "family": {
        "children": [
            [
                "Alex",
                24
            ],
            [
                "Kate",
                12
            ]
        ],
        "u_salary_1_5_year": 3200
    },
    "name": "Aleksei",
    "salary": 800
}
```

3. EP_3  
Method: `GET`  
EndPoint: `/object_info_1`  
request url params:   
name: `Aleksei`  
age: `33`  
weight: `77`  
```json
{
    "age": 33,
    "daily_food": 0.924,
    "daily_sleep": 192.5,
    "name": "Aleksei"
}
```   

4. EP_4  
Method: `GET`  
EndPoint: `/object_info_2`  
request url params:   
 name: `Aleksei`  
 age: `33`  
 salary: `800`   
 ```json
 {
    "person": {
        "u_age": 33,
        "u_name": [
            "Aleksei",
            800,
            33
        ],
        "u_salary_5_years": 3360.0
    },
    "qa_salary_after_1.5_year": 2640.0,
    "qa_salary_after_12_months": 2160.0,
    "qa_salary_after_3.5_years": 3040.0,
    "qa_salary_after_6_months": 1600,
    "start_qa_salary": 800
}  
```  

5. EP_5  
Method: `GET`    
EndPoint: `/object_info_3`    
request url params:   
 name: `Aleksei`    
 age: `33`  
 salary: `800`   
 ```json 
 {
    "age": "33",
    "family": {
        "children": [
            [
                "Alex",
                24
            ],
            [
                "Kate",
                12
            ]
        ],
        "pets": {
            "cat": {
                "age": 3,
                "name": "Sunny"
            },
            "dog": {
                "age": 4,
                "name": "Luky"
            }
        },
        "u_salary_1_5_year": 3200
    },
    "name": "Aleksei",
    "salary": 800
}   
```   

6. EP_6  
Method: `GET`   
EndPoint: `/object_info_4`   
request url params:    
 name: `Aleksei`   
 age: `33`   
 salary: `800`   
 ```json 
 {
    "age": 33,
    "name": "Aleksei",
    "salary": [
        800,
        "1600",
        "2400"
    ]
}  
```   

7. EP_7      
Method: `POST`    
EndPoint: `/user_info_2`   
request form data:     
 name: `Aleksei`      
 age: `33`      
 salary: `800`      
 ```json  
 {
    "person": {
        "u_age": 33,
        "u_name": [
            "Aleksei",
            800,
            33
        ],
        "u_salary_5_years": 3360.0
    },
    "qa_salary_after_1.5_year": 2640.0,
    "qa_salary_after_12_months": 2160.0,
    "qa_salary_after_3.5_years": 3040.0,
    "qa_salary_after_6_months": 1600,
    "start_qa_salary": 800
}   
```   


