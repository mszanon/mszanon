# Implementation:

### Q) What libraries did you add to react-native? What are they used for?
I’ve made my best to keep as simple as possible so Im just using the expo-screen-orientation
and the react-native-device-detection, just to make the app better on tablets devices. Im also using the basics dependencies for jest.

You can find how it should looks like at the assets folder.

### Q) What's the command to start the application locally?
please navigate to mobile folder and run ‘npm i’, so ‘expo start’. 
if you want to run the app on other devices, after ‘expo start’ command you can hold shit and press either 'i' for iOS devices or 'a' for android devices. thats all depends what about which simulators you have installed on your device. 

you also have the options to pass the flags like 'expo start --android' or 'expo start --ios'to run straigh on the choose platform.

This app has been tested on both Android (28, 29 and 30 ) and iOS, both on landscape and portrait mode.

There are also unit tests available. To execute it, please run 'npm run test'

### Q) Any other comments we should read before evaluating your solution?
In my implementation the user is able to pick a toggle (either available on US or has not test mode, or both) and able to shuffle the same list as many time he wants without breaking the other options.

# General:

### Q) If you had more time, what further improvements or new features would you add?
First I would improve the flatlist performance, either by backend pagination or a deeper optimization on the frontend. I would start a long term project with storybook and decide with my colleagues our approach to the main implementation. And I would make use of reducers and dispatching actions with a more friendly UI kit.

### Q) Which parts are you most proud of? And why?
To escape my redux zone and think the project with an API I never tried before. So I did not had that much time to learn Context API. Hope its fine but I understand it can be better.

### Q) Which parts did you spend the most time with? What did you find most difficult?
Basically to figure out a better user experience using a new API.


### Q) How did you find the test overall? Did you have any issues or have difficulties completing? If you have any suggestions on how we can improve the test, we'd love to hear them.
Honestly, I loved the test. Sounds simple but its tricky at same time. I had my issues while I was implementing all the filters at same time with context API. For me would be a 1 hour task if I was on my current stack (Saga, redux), but I decided to try a new approach  with a clean code. I learned a lot with it.

Im super thankful for that.