# Car rental
CRUD application realizing car rental management system functionality.


## Table of Contents
- [Prerequisites](#prerequisites)
- [Getting Started](#getting_started)
- [Application Preview](#application_preview)

## Prerequisites <a name = "prerequisites"></a>

`java 11` https://www.oracle.com/pl/java/technologies/javase-downloads.html
<br/>`docker with docker-compose` https://docs.docker.com/get-docker/

## Getting Started (Ubuntu) <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Installing

Cloning project:
```
$ cd <place-you-want-to-store-car_rental>
$ git clone https://github.com/Konrad-Abramowski/Car_rental.git
$ cd Car_rental
```

Running postgreSQL database on localhost:5432:
```
$ sudo docker-compose up -d
```
Running the application:
```
$ ./mvnw javafx:run
```
## Application Preview <a name = "application_preview"></a>
| ![logowanie_rejestracja](https://user-images.githubusercontent.com/49612999/112478776-a17d5380-8d74-11eb-961f-7e787c800c56.png)|  
|:--:| 
| *Image1: Login window* |
  
| ![panel_klienta](https://user-images.githubusercontent.com/49612999/112479207-19e41480-8d75-11eb-8000-e33a3a657b16.png)|  
|:--:| 
| *Image2: Main client panel* |

| ![zarzadzanie_koszykiem](https://user-images.githubusercontent.com/49612999/112479501-63ccfa80-8d75-11eb-8dac-6cd287d8b65f.png)|  
|:--:| 
| *Image3: Shopping cart window* |

| ![tworzenie_rezerwacji](https://user-images.githubusercontent.com/49612999/112479787-a7bfff80-8d75-11eb-9139-5b0ff7455c71.png)|
|:--:| 
| *Image4: Make a reservation window*  |

| ![panel_pracownika](https://user-images.githubusercontent.com/49612999/112480608-7eec3a00-8d76-11eb-863e-3b9823752f8a.png)|  
|:--:| 
| *Image5: Main employee panel* |

| ![dodawanie_samochodu](https://user-images.githubusercontent.com/49612999/112481284-223d4f00-8d77-11eb-9d9c-e5391b31e2cb.png)|  
|:--:| 
| *Image6: Adding new car to catalog window* |
