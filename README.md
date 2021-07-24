 C - 82
 
 This project is created by Aditya Srivastava
 
 In this project we have 
 Import stack navigator from react-navigation-stack and create a
 stackNavigator.
 Add our AppDrawerNavigator and UserDetails screen to it. In Navigation
 options set headerShown as false.
 In Exchange screen write a new function called createUniqueId() which will
 generate a random string of 5 characters and set it to “exchangeId” field in
 state. Also add this field to the addItems() function.
 From HomeScreen pass item description, userId to the UserDetails screen.
 Receive these fields in state using this.props.navigation.state.params.
 In User details screen write a function getUserDetails() which will query on
 the database using the username to get the data of the user and store it in
 state.
 Write a function called addBarters() which will create a new collection called
“MyBarters”. This collection will contain the item name, Exchanger Name,
 Exchanger Contact, Exchanger Address, Exchange Id and the status of
 exchange. Call this function on the “Exchange” button press.
 Create a new screen called “My Barters” and add it to the
 AppDrawerNavigator.
 In “My Barters” screen write a function called getAllBarters() which will
 query the database and get all the barters from the collection “MyBarters”.
 Map on the data received by getAllBarters() and display it using a flatlist.
 Create a button called “Exchange” in each barter request.
 Thanks 😃
