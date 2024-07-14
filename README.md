### Airbnb prices analysis in European cities  

Pet-project where I analyze the Airbnb prices in 10 European cities and the determinants of price. I used a dataset from [Kaggle](https://www.kaggle.com/datasets/thedevastator/airbnb-prices-in-european-cities/data)  

Ціллю мого PET-проекту є аналіз цін на Airbnb у 10 містах європи в будні і вихідні дні, а також визначення факторів, які впливають на рівень цін.  

Засоби та методи  аналізу: В дата-сеті було 20 таблиць - по 2 таблиці на кожне місто - з цінами в будні і вихідні дня. Спочатку я дослідила вміст таблиць і стовпчиків у  Google BigQuery за допомогою SQL-запитів. Оскільки в даних не було ключів і в Google BigQuery не підтримує складені ключі, то було прийнято рішення використати Python для обробки даних. В Python за допомогою складеного ключа я визначила помешкання, які доступні і в вихідні і в будні, створила стовпчик з містами і об'єднала дані таким чином, щоб помешкання не повторювались в моємо об'єднаному дата-сеті. Наступним кроком була додаткова обробка даних в Python - створення додаткових стовпчиків і прибирання зайвих, округлення. Також в Python було проведення дослідження кореляції між різними показниками в цілому і між ціною по будням/ціною по вихідним і показниками. Для візуаліції я обрала Tableau. 

На основі проведеного аналізу було виявлено наступне:  
