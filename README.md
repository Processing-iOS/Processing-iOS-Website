Processing for iOS is an iOS editor of the popular programming language processing.org.

### Simple and powerful processing programming language

```Processing
size(300, 260);

background(255); // white

int x = Math.floor( Math.random() * 300 );
int y = Math.floor( Math.random() * 260 );

int colour;

for (int i=0; i<30000; i++)
{
   int vertex = Math.floor(Math.random() * 3);
   switch (vertex)
   {
      case 0:
      x = x / 2;
      y = y / 2;
      colour = #00ff00; // green
      break;
      case 1:
      x = 150 + ( 150 - x )/2;
      y = 260 - ( 260 - y )/2;
      colour = #ff0000; // red
      break;
      case 2:
      x = 300 - ( 300 - x )/2;
      y = y / 2;
      colour = #0000ff; // blue
   }
   set(x, y, colour);
}
```


### Powerful native iOS add-ons

- accelerometer and gyroscope access
- compass
- barometer
- camera

### Open Source

Get involved and help improving processing for iOS. The project is available on [GitHub](https://github.com/Processing-iOS/Processing-iOS).

### Community!

You created an awesome piece of software in Processing for iOS? You are using Processing for iOS to teach students programming?
I would love to hear about that: frederik@processing-app.org
