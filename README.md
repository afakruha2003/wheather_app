# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
#--------------------------------------------------------------------------------------------------------------
# Staj-Proje-001: Hava Durumu Uygulaması

## Açıklama

Bu proje, bir hava durumu uygulaması oluşturmayı hedeflemektedir.

## Son Tarih

05.11.2024

## Problem Tanımı
Portföylerimize yeni bir proje ekliyoruz. Bu nedenle, siz ve meslektaşlarınız projede çalışmaya başladınız.

## Proje Yapısı

```
Weather App (folder)
|
├── public
│     └── index.html
├── src
│    ├── components
│    │       ├── cards
│    │            ├── Card.css
│    │            └── Card.jsx
│    │       
│    ├── images
│    │       └── logo.png
|    |
|    |
│    ├── App.js
│    ├── App.css
│    ├── index.js
│    └── index.css
|
├── package.json
├── package-lock.lock
└── README.md

```


## Beklenen Çıktı

![Proje 001 Ekran Görüntüsü](weather-app.gif)

## Hedef

ReactJS kullanarak bir Hava Durumu Uygulama Projesi oluşturun.

### Projenin sonunda, aşağıdaki konular ele alınacaktır;

- HTML
- CSS
- JS
- ReactJS
- Bootstrap
- Fetch API

### Projenin sonunda, öğrenciler;

- HTML & CSS & JS & ReactJS içinde kodlama becerilerini geliştirebilecek.
- OpenWeather API'den veri almak için fetch yapısını kullanabilecek.

## Çözüme Giden Adımlar

1. `npx create-react-app weather-app` kullanarak React Uygulaması oluşturun.
2. OpenWeather API'de bir hesap oluşturun ve ücretsiz bir API Erişim Anahtarı alın.
3. API'den hava durumu bilgisi almak için bir fonksiyon tanımlayın: 
    `https://api.openweathermap.org/data/2.5/weather?q=${place}&appid=${tokenKey}&units=metric&lang=tr`
    Örnek URL: `https://api.openweathermap.org/data/2.5/weather?q=Ankara&appid=${tokenKey}&units=metric&lang=tr`
    (tokenKey, erişim anahtarınızla değişecektir)
4. Hava Durumu ikonlarina ulasmak icin hava durumu verisi icerisindeki weather listesi icerisindeki icon datasini kullanabilirsiniz.
    Ornek src: `http://openweathermap.org/img/wn/${icon}@2x.png`;
5. Bir şehir için Hava Durumu Verilerini görüntülemek için bir kart bileşeni oluşturun.
6. Gösterim için aranan şehirleri bir liste içinde kaydedin.

## Notlar

**<p align="center">&#9786; Mutlu Kodlamalar &#9997;</p>**


