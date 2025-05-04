<h1>CS 408 - Final Project</h1>
<h3>By Austin Andersen</h3>

<br>

<h2>General Theme</h2>
<p>My idea for the project is to create an application that would be used in hotels by front desk staff, as I am a night auditor myself at a hotel. I've been intending on making some sort of application that is 
  better than what we currently use. I've been talking previously to a coworker of mine about taking on a project like this to see if I can make a website that has better features, and to improve upon existing ones.
  While I might not be able to make a fully functioning application the way that I want to, I thought that with the project specifications of making a workable website that integrates AWS, I could at least make a
  dumbed down version, and try my hand at it.</p>

<h2>Features</h2>
<p>The base features that I want to include is that I want to be able to store guest information on my database. I want to be able to access guest information, and to "check-out" guests by either deleting them 
  from the database altogether, or having some sort of flag on these reservations that indicates whether they are incoming arrivals, currently checked-in, or past guests. If I have time and am able to do so, I
  would also like to add some additional features, such as a bulk checkout. This feature in the current application I use is implmented incorrectly, and doesn't allow you to select what guests specifically you 
  would like to check out. Instead, it makes you check out everyone, which obviously is not useful and any situation.</p>

  <h2>Target Audience</h2>
  <p>The target audience for this website would be hotel staff who use this application.</p>

  <h2>Data to be Used</h2>
  <p>Data that will be stored in my database will include first and last names, phone numbers, emails, check-in and check-out dates, reservation notes, and potentially a list of room charges. If you are looking
    for check-outs, it will pull any reservations with departure date on the current date. If you are looking for check-ins, it will do the same thing, looking at arrival date. If I'm able to implement it in time,
    I would like to be able to arrange room charges and create an invoice that can be sent out to the guest.</p>

  <h2>Additional Features</h2>
  <p>As I said, I would like to make sure that I can get the check-in and check-out feature to work. If I am able to, I want to add the bulk checkout feature, a feature to create a personalized invoice, and a search feature.</p>

<h2>Website Wireframe</h2>
<img src="webdesign.png" alt="wireframe">

<h2>Overview of Finished Project</h2>
<p>The finished project consists of the following files:</p>
<h3>HTML</h3>
<li>dashboard.html</li>
<li>list.html</li>
<li>staycard.html</li>
<li>newReservation.html</li>
<h3>CSS</h3>
<li>dashboard.css</li>
<li>list.css</li>
<li>staycard.css</li>
<li>newReservation.css</li>
<br></br>
<p>The project is meant to be ran from the dashboard.html file, which is the landing page of my website. While unfortunately I was unable to add functionality of all the elements on the front page due to time constraints, I was able to add functionality to the new reservation button and the arrivals button. While the arrivals button doesn't function exactly as it is supposed to, it displays all reservations in the database.</P>
<p> The "NEW" button will direct you to the newReservation.html page, and will allow you to put in the desired guest information. You can then hit the "Book" button to submit the data.</p>
<p>Submitting a new booking will then bring you to the new guest's staycard, which is rendered using the staycard.html page. This will display the guest information in an easy-to-read format. It also had a "Delete Guest" button on the bottom of the page, which removes the guest from the database, and either takes you back to the dashboard if you had just made that new guest, or brings you back to the arrivals page.</p>
<p>The final page is the arrivals page which is displayed by the list.html file. Currently all the buttons on the dashboard link to list.html and display all reservations, which is not the intended result but again, due to time constraints I couldn't finish that part of the project as I had planned. Currently list.html displays all reservations, which can be individaully clicked on to bring up that guest's staycard, or the "Dashboard" button can be clicked to bring you back to the dashboard.</p>
<p>All the Javascript code was written as scripts on the html files, and each css file corresponds to the html file with the matching name.</p>