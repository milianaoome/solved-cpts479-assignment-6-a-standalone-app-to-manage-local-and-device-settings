Download Link: https://assignmentchef.com/product/solved-cpts479-assignment-6-a-standalone-app-to-manage-local-and-device-settings
<br>
For this homework you will implement a standalone app to manage local and device settings for the Quiz App. This should be a new Xcode project, not an addition to a previous Quiz app. You will manage three local settings: user name, whether to shuffle questions, and the time limit for each question. You will manage two device settings: quiz category, and whether to automatically download new content. All these settings should be stored in the UserDefaults singleton class and persist even if the app is terminated and restarted. See screenshots below. Specifically,

<ol>

 <li>Create a new Xcode project called QuizApp that consists of a Navigation Controller and a Settings Table View Controller. The navigation bar should have prompt “Quiz App” and title “Settings”. The table should have static content with two groups (“LOCAL SETTINGS” and “DEVICE SETTINGS”).</li>

 <li>Add a Settings Bundle to your app. Modify the Root.plist under the Settings.bundle to contain a multi-value item for the setting “Category” with at least the titles “All”, “Movies”, “Science”, and “Sports”. The default value should be “All”. You can add more categories if you want. Also add a toggle switch titled “Auto Download”. The default value should be “YES”.</li>

 <li>In the table view, the first group “LOCAL SETTINGS” should have three rows as follows:

  <ol>

   <li>The first row has a Username label and a text field to change the username. Upon tapping return on the keyboard, the keyboard should disappear and the username setting should be updated. The initial default setting should be the empty string.</li>

   <li>The second row has a Shuffle label, showing the status as “Yes” or “No”, and a switch to change the shuffle status. The initial default setting should be “Yes”.</li>

   <li>The third row has a Time Limit label, showing the number of seconds, and a stepper to change it. The stepper should range from 1 to 30. The initial default setting should be 5 seconds.</li>

  </ol></li>

 <li>The second group “DEVICE SETTINGS” should have two rows: a Category label showing the category, and an Auto Download label showing whether it is “On” or “Off”. Tapping on one of these rows should take you to the Device Settings page for this app. Any changes to the Device Settings for this app should be immediately reflected in the app’s Settings table view when you return to the app.</li>

</ol>

1

<ol start="5">

 <li>You are recommended to test your final app by first removing it from the simulator/test device, so that all previously-defined UserDefaults are also removed, and then reinstalling/rerunning the app to verify correct behavior.</li>

 <li>Be sure that auto layout constraints are set so that the view elements are appropriately displayed with no overlap regardless of device orientation.</li>

</ol>




StoryBoard:




Simulator: