# CrimeCatch
final-project-weblogix created by GitHub Classroom

**Description**

• Crime Catch was an exciting web-project that was built using Angular at the front-end and NodeJs as the back-end and a shared MongoDB cloud storage.

• The goal of this project was personally inspired being an international student in the United States to help every student or any individuals find a safe area/street while traveling or searching accommodation, etc.

• This was accomplished by first obtaining a crimes data-set for Boston, MA from kaggle.com and then integrating with Angular Google Maps providing filter by crimes or streets.

• Another SOS feature was added using NodeMailer to help individuals to alert its emergency contact providing the current location during any time of crisis. Apart from these, Angular Material Design was used for forms and validations; PassportJS and JWT token for authentication; ChartJS for displaying different types of analysis, NewsAPI for providing result based real-time news feed to the user.

**Citizen**

<table class="tg">
  <tr>
    <th class="tg-0pky">USER STORY</th>
    <th class="tg-c3ow">ACCEPTANCE CRITERIA</th>
  </tr>
  <tr>
    <td class="tg-0pky">Unregistered user should see the link for sign up to get access to features present on the website</td>
    <td class="tg-0pky">#Sign up button should appear on the home page<br>#User should get successfully navigated to the sign up form page</td>
  </tr>
  <tr>
    <td class="tg-0pky">Unregistered user should be able to enroll herself/himself by filling up the sign up form</td>
    <td class="tg-0pky">#User should encounter sign up form<br>#User should enter his/her email address which will be treated as username for further logins by the same user<br>#User can set password of their choice considering the given guidelines<br>#User must re-enter the password for validation<br>#User can also fill up the non mandatory fields present on the form</td>
  </tr>
  <tr>
    <td class="tg-0pky">Registered user should see the link for sign in for login in into the website</td>
    <td class="tg-0pky">#Login button should appear on the home page<br>#User should get successfully  navigated to login form page<br>#User should enter correct username with the parallel password in order to get authenticated</td>
  </tr>
  <tr>
    <td class="tg-0pky">“Fact” tab should be visible to user in the navigation bar of the website</td>
    <td class="tg-0pky">#Facts tab should appear on the navigation bar of the website<br>#On click of the link user will be navigated to a page where user can apply filters in order to view plot crimes in graphs based on the parameters provided</td>
  </tr>
  <tr>
    <td class="tg-0pky">“View crimes” tab should be visible to user in the navigation bar of the website</td>
    <td class="tg-0pky">#On click of the link user will be navigated to a page where user should see live map of the locality and makers should be displayed on the maps based on the filter applied</td>
  </tr>
  <tr>
    <td class="tg-0pky">“Report crime” tab should be visible to user in the navigation bar of the website</td>
    <td class="tg-0pky">#On click of the link user will be navigated to a page where user can report crimes encountered by the user by providing details expected in the form on the page<br>#User should receive text message once the status of the reported request is changed</td>
  </tr>
  <tr>
    <td class="tg-0pky">“Create alerts” tab should be visible to user in the navigation bar of the website</td>
    <td class="tg-0pky">#On click of the link user will be navigated to a page where user can create alerts based on the selected location <br>#Subscribed user should receive text message in an event of alert broadcast by authority</td>
  </tr>
  <tr>
    <td class="tg-0pky">“Read news feed” tab should be visible to user in the navigation bar of the website</td>
    <td class="tg-0pky">#On click of the link user will be navigated to a page where user should see updated news fields <br>#Only registered user should be able to place comment on the news blog<br>#Unregistered user should be prompted with the signup/login page before placing comment</td>
  </tr>
  <tr>
    <td class="tg-0pky">“Share my current location” tab should be visible to user in the navigation bar of the website</td>
    <td class="tg-0pky">#On click of the link user will be navigated to a page where user can share their live location to other user<br>#Other user should receive a link from which  location can be tracked on maps</td>
  </tr>
</table>

**Police**

<table class="tg">
  <tr>
    <th class="tg-0pky">USER STORY</th>
    <th class="tg-c3ow">ACCEPTANCE CRITERIA</th>
  </tr>
  <tr>
    <td class="tg-0pky">“Accept citizen” tab should be visible to user in the navigation bar of the website<br></td>
    <td class="tg-0pky">#User should see the pending request by the citizen <br>#User can click “accept” or “decline” buttons after authenticating the user<br>#User profile of the citizen should be created based on click action of the user<br></td>
  </tr>
  <tr>
    <td class="tg-0pky">“Verify reported incident” tab should be visible to user in the navigation bar of the website<br></td>
    <td class="tg-0pky">#User should see the pending reported crime list by the citizen<br>#User can click “accept” or “decline” buttons after verification of  the incident <br>#Case should be filed based on the action of the user<br></td>
  </tr>
  <tr>
    <td class="tg-0pky">“View incidents” tab should be visible to the user in the navigation bar of the website<br></td>
    <td class="tg-0pky">#All the existing reported crimes by the citizen should be listed on the page<br>#By clicking on the incident, user can view details of the incident<br>#User can also update the status of the incident reported<br></td>
  </tr>
</table>

**Domain Driven Design -1**
![alt-text](https://github.com/neu-mis-info6150-fall-2018/final-project-weblogix/blob/master/Web%20Assignment.svg)

**Domain Driven Design -2 (ER Diagram)**
![alt-text](https://github.com/neu-mis-info6150-fall-2018/final-project-weblogix/blob/master/Web.svg)
