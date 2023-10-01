# JamStack

## - What is this JAMstack?
JAMstack is a software architecture and philosophy. Its history stems from growing the term "static site" into something more meaningful (and marketable). So while ultimately a static site is the end result, it's blown up to include first class tooling for every step of the way.

## - components: 
1- Javascript
2- APIs
3- Markup

![img](https://www.freecodecamp.org/news/content/images/2020/02/jamstack-breakdown-3.jpg)

## - what makes a JAMstack app so great?
JAMstack apps inherently satisfy most if not all of the 5 pillars of the AWS Well-Architected Framework. These are core concepts that AWS considers to deliver fast, secure, high-performing, resilient, and efficient infrastructure.

### 1- Speed
The fact that you’re serving JAMstack apps as static files directly from a CDN (usually) makes it likely your app is going to load super fast. 

### 2- Cost
More often than not, JAMstack sites are going to run cheaper than their server side counterparts. Hosting static assets is cheap and now your page is being served at the same rate.

### 3- Scalability
Since you’re serving your files off of static hosting, likely a CDN, that pretty much automatically gives you infinite scalability. Most providers will make this claim, meaning you’ll have no trouble letting any influx of people hitting your site in through the front door.

### 4- Maintenance
The foundation of your static site isn’t a server, meaning you don't need to maintain it. Whether it’s Netlify, S3, or any other provider, your static HTML, CSS, and JS are maintained for you headache-free.

### 5- Security
Doubling down on the lack of server that you have to personally maintain, you don’t really need to worry as much about locking down ways for people to intrude.

