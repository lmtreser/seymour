# Making active members of your team out of your office plants

Ever since we moved to our first office we knew that having nice and healthy plants would help us to bring a livable and positive atmosphere to the workplace. We got a few of them and put them in nice and well lit places around the office. We only had to water them from time to time and that was it!
Not being plant people ourselves, we kinda neglected them. Some would get too much water too frequently and others would get just a fraction of what they actually needed. Without proper care, the sight of decaying, dry plants caused the opposite effect that we initially intended. Unfortunately not all of them made it until the end of that year. It would have been great if they could simply tell us when they need water, right? But plants can’t talk… or can they?

![img1](docs/img/img1.jpeg)

## The idea

On February 12, 2016 an Internet of Things hackathon was held in our city by [SUMA Conectivo](https://web.archive.org/web/20160426044837/http://sumaconectivo.org/index.html). Together with [Lucas](https://twitter.com/lmtreser) and [Jose Luis](http://www.roboticaeducativa.com/) we decided to find a solution to this problem. Even though many solutions already exist, we did it the same because we enjoyed the challenge and we knew that we could find a nice solution together. The idea was to develop both an Internet of Things (IoT) solution to give plants the ability to tell us when they were thirsty.
The idea of having plants that can talk to us and tell us when they are hungry inmediately reminded me of the classic Little Shop of Horrors movie, so the project was called Seymour as an homage to the flower shop attendant who took care of Audrey II, a hungry plant with a very special taste for food.

## The solution

The project consists of several components. Two metallic pins are inserted in the dry dirt of a flower pot. Since there is a direct relation between humidity and conductivity, we used an Arduino to read conductivity levels at periodic intervals.
