# Eyes

Is an application where I show my ability to use simple animations together with CSS and some events.

## Installation

Still learning how to deploy applications.

```bash
npm install eyes
```

## Usage

```python
import eyes

# how to use pacment
var balls = document.getElementsByClassName("ball");
    document.onmousemove = () => {
      var x = (event.clientX * 100) / window.innerWidth + "%";
      var y = (event.clientY * 100) / window.innerHeight + "%";

      for (let i = 0; balls.length; i++) {
        balls[i].style.left = x;
        balls[i].style.top = y;
        balls[i].transfoorm = "translate(-" + x + ",-" + y + ")";
      }
    }
```

## Contributing

I will keep working on this project and any contibutions is as well welcome.

Please make sure to update eyes as appropriate.

## Authors and acknowledgment
Thanks to my Professional Certificate in Coding: Full Stack Development with MERN professors
and all the people that makes this course possible.

## License

[MIT](https://choosealicense.com/licenses/mit/)
