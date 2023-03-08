# Raman Sliapukhin

## Contact Me

- [Email](mailto:rsliapwebd@gmail.com)
- [Github](https://https://github.com/rsliapwebd)

## About Me

Self-taught web developer. Always trying something new.

## Skills

HTML, CSS, JavaScript

## Code example

```js
// Get weather data
const getWeatherData = async function (obj) {
  try {
    const jsonData = await fetch(
      `https://api.openweathermap.org/data/2.5/weather?lat=${obj.lat}&lon=${obj.long}&appid=c4fd4dbbe8a63984662de3192f30f560`
    );
    const data = await jsonData.json();
    renderInfo(data);
  } catch (err) {
    alert("Somethimg went wrong :(");
  }
};
```

## Experience

- [The Odin Project](https://rsliapwebd.github.io/theodinproject/)

## Education

Environmental Engineer, Francisk Skorina Gomel State University, 2013

## Languages

- Belarusian
- English B2
- Russian
