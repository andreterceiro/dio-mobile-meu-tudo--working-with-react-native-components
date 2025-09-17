# Introduction

In the introduction, teacher reinforced that React (and React Native) uses several components and when we program a mobile application we do not create a component by scratch. Instead of this we build an application using pre builded components.


# Repository related to the group of classes

[link](https://github.com/digitalinnovationone/trilha-react-native-components)


# Creating a new app

Teacher asked us to run the following command (seems equal to the previous command he passed):

```
npx create expo app components-overview -t
```

And in the question in the terminal about how template to use please select "Blank (TypeScript).

In the next steps in the introduction teacher only accessed the directory created by the previous command and run the following command:

```
npm run start
```

Teacher had to open an emulator in Android Studio. Then in the terminal of the previous command he clicked in the option "a" to run the app in the Android emulator.

Then the blank app was showed in the Android emulator.


# View

Teacher teached us that a View is equivalent to a "<div />" in HTML world.

In the next image teacher showed some examples of <View>s in a cellphone screen:

![View](images/View.png)


## Touching on a View

Teacher showed an example of handle touches in a View without a TouchableOpacity

![View - touches](images/View-touch.png)

Teacher also said that instead of an inline function you could use an external function as a handler.

A little comment: you could see in the image teacher dealing with a touch star and a touch end events.


## Documentation

Teacher showed that we can see more about views (selection in the left part of the image) and its events (selection in the right part of the image).

![documentation](images/documentation.png)

Teacher also teached that as you can see in the next image some events are specifically related to a platform (Android in the next image):

![android specific event](images/android-specific-event.png)


# Text

Teacher said that if you wanna to output a text in the app you must use the Text component:

![without text = error](images/without-text-error.png)

And you could also use the Text component to other different thing, like simulating a button.

![text simulating a button](images/text-simulating-a-button.png)

# External link

Teacher also passed [this link about components and APIs](https://reactnative.dev/docs/components-and-apis) in the complimentary materials area.