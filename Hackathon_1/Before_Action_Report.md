#:clock12: 00:00

Ok so we are about 24 hours away from the hackathon. In 6 hours it will be 06:00, add another 6 and we are sitting at 12:00. Half the day has passed. This is why we use military time. 

It really helps you to visualize a concept like a day

:sunrise::sunrise_over_mountains::city_sunset::stars: 


into something concrete like an array

```swift
let day: [Int] = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23]
```

You see how 17:00 "feels" later than 05:00

Alright so I have 24 of these boxes or compartments of time to do stuff. Sleep, exercise, read, code, plan stuff, do things I've been putting off, errands, time with friends and family. I can't do them all so some things have high priority and low priority. I have to allocate my 24 boxes of time very carefully before this hackathon. Things below a certain threshold get tossed out immediately. So no :no_good::see_no_evil::beers::tada::video_game:


Things must have a priority level of 8 and above to receive any resources (time).

So I need 6 hours of sleep, 1 hour of excercise and down the line from highest to lowest

```swift
  let sleep: Double = (24 * 0.25) // 6 compartments
  let excercise: Double = (24 * 0.04166666667 // 1 hour; I think; approximate)
  let researchApi: Double = (24 * 0.25) // about 4 - 6 compartments
  ...
```

