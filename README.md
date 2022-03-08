# react-language-cards

# Getting Started with Create React App
    npx create-react-app react-language-cards
   
   cd react-language-cards
   npm start

## npm install node-sass
# Getting Started with Create React App
    npx create-react-app react-language-cards
   
   cd react-language-cards
   npm start

## npm install node-sass

![](foto/giris1.jpg)
![](foto/giris2.jpg)


prole içinde iki tane componenet kullanacağız. bunlardan önce data.js lerimizi oluşturalım. assets klasörümüz projenin fotoğraqflarını tutuyor.
data.js dosyasında categories değişkeniyle export edilimiş array imiz var. projenin data bilgilerini tutuyor.

## data.js


import css from "../assets/css.png";
import python from "../assets/python.png";
import java from "../assets/java.png";
import cpp from "../assets/cpp.png";
import go from "../assets/go.png";
import php from "../assets/php.png";
import javascript from "../assets/javascript.png";
import html from "../assets/html.png";



export const categories = [
    {
      name: "javascript",
      img: javascript,
      infos: ["Website Development", "1995", "Brendan Eich"],
    },
    {
      name: "html",
      img: html,
      infos: ["Website Development", "1993", "Tim Berners-Lee"],
    },
    {
      name: "css",
      img: css,
      infos: ["Website Design", "1994", "Håkon Wium Lie"],
    },
    {
      name: "python",
      img: python,
      infos: ["AI", "1980", "Guido van Rossum"],
    },
    {
      name: "java",
      img: java,
      infos: ["BackEnd", "1990s", "Sun Microsystems"],
    },
    {
      name: "c++",
      img: cpp,
      infos: ["Game Dev.", "1980s", "Bjarne Stroustrup"],
    },
    {
      name: "go",
      img: go,
      infos: ["Network", "2009", "Robert Griesemer"],
    },
    {
      name: "php",
      img: php,
      infos: ["BackEnd", "1995", "	Rasmus Lerdorf"],
    },
  ];

  öncelikle header componentini yazmaya başlayalım