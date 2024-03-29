#This is a course project for CSC207, collectively done by me and my teammates.

In order to run this program, please go to phase2/controller/MainApp
and run MainApp file.

For testing purposes, you may need to change your system time. But please don't
change it in any backward manner.

If you already have an account, sign in by entering your username and password.

Or sign up by clicking the Sign up button to enter the sign up page. Enter your
username and password, then choose your role in the box below.

!NOTE: for some user type may have additional requirement in order to sign up,
for detail of each, please refer to the corresponding user instruction below.

If you wish to test this program. We suggest you to sign up users in this order
for convenience:
        Administrator -> Coordinator -> Interviewer -> Applicant -> *Referee

For each type of user, you can sign out anytime you want. There is no need to
save.



Applicant User:

- To view or add your CV and CoverLetter, please go to 'My Profile' page. You
  Can choose to enter by typing them in the text fields or upload a txt by
  hitting the upload button.(this feature only support *.txt file)

  Note: CV and CoverLetter will be deleted from system automatically in 30 days.

- To apply for a posting, go to 'Browse Posting' page.

  There is a search by tags feature which you can see on the right. Select the
  tags you prefer (you can select multiple tags), then press filter button.
  The corresponding posting will show up.

  If you would like to see all posting again, press the clear button.

  Left click a posting to select and hit the apply button to apply. Then choose
  your CV and CoverLetter.

  Some posting require a number of reference letters from referee. You can enter
  the Email addresses of referees to request reference letters   from them.

  If this requirement is not satisfied by the document deadline (ex. The referee
  did not upload the reference letter for this applicant in time). This applicant
  will be automatically disqualified.

  After you have done everything, hit apply.

- To view or withdraw your application, go to 'My Application'. Choose your
  application and press withdraw.

- To view your inbox, go to 'My inbox'. You will receive notification when:

        - You have a new interview.

        - You have received a reference letter.

        - You have been hired.

        - You have been rejected.


Interviewer User:

- To view all your upcoming interviews, go to 'incomplete interviews'. Double
  click on applicant to view their CV, CoverLetter, and Reference Letter.

  For Phone, one to one, and group interview, you need to either recommend or
  un-recommend the applicants.

  For Quiz interview, you will set a mark for the applicants.

- To view the completed interviews. Go to interview history. Select the
  interview and double click on the applicant to view their info.

- To view your inbox, go to 'My inbox'. You will receive notification when:

        - The administrator has made an announcement.

        - You have an upcoming interview.

        - You have been registered to the company by administrator.


Coordinator User:

  SIGN UP REQUIREMENT:

  You need to enter your company name during sign up. After receiving approval
  from your administrator, you will be able to login.


- To post a new job posting, go to the 'Create Post' tab.

  Enter title, content, application close day, reference deadline day, number
  of reference required, and the number of people hiring in their corresponding
  text field.

  Set the format of the interview process by pressing 'Set Interview'. You can
  set different interview type for each round.

  Phone interview/ one to one interview:
        interviewer will recommend or un-recommend the applicants to go to the
        next round.

  Group interview:
        A group of interviewers will evaluate a group of applicants. Interviewers
        will make their recommendations for the applicants. Only applicants that
        receive enough recommendations(a number that you can set) will proceed
        to the next round.

  Quiz Interview:
        The assigned interviewer will mark each applicant. You will set a threshold
        of people that can proceed to next round. Only applicant with top marks
        will go into next round.

  Tags are optional when creating post. You can edit tag by pressing "Set Tags".
  By default, a posting will automatically be tagged with the company's name
  and its location.


- To view or modify your posting, go to 'Check Post' page, select a posting
  and hit 'view'.

  You can modify all fields of a job posting 

  To see a list of applicants that have applied for this posting, press the
  'See Applicant' button.

  Select the applicant in the table and press 'view' to see their CV and
  CoverLetter, and which job postings they have applied for.

  You can also remove a particular application.

- The Manage Interview page will allow you to match interviewers with applicants.
  You can do that by select the posting, go to the current round of interview by
  selecting the tab at the top, then hit 'create interview'.

  NOTE:
        When a new round started, if number of applicants remaining is less or
        equal to number of people you are hiring for this job, then applicants
        will be hired automatically.

        When the last round has ended, if number of applicants remaining is more
        than you are hiring, double click on the applicants to see the pop up
        window which then you will be able to hire them.

- To view your inbox, go to 'My inbox'. You will receive notification when:

        - The administrator has made an announcement.

        - You have been registered to the company by administrator.



Referee:

  SIGN UP REQUIREMENT:

  A referee will only be available to sign up after an applicant has request a reference
  letter from you by entering you Email. You will be given a initial password "default",
  which you can use to login in directly, or go to the sign up page to change it.

  - In 'Incomplete Application', you will see all the request that you have received but
    not yet fulfilled. Double click on each application to see details such as deadline.

    You can either enter from text field or upload a txt file.

  - 'Complete Application' stores the requests you have fulfilled. Double click on each
    to see the reference letter you have written for them.

  - To view your inbox, go to 'My inbox'. You will receive notification when:

          - You have received a new reference letter request.


Administer:

  SIGN UP REQUIREMENT:

  You need to enter the name of your company during sign up.

  - First thing you need to do is add a location (or branch name) for your company,
    enter the name in corresponding text field and press 'add'.

    When there are new coordinators available for you to assign. Select one of the
    location, then choose the coordinator from choice box and press 'add'.

    This will approve them to represent your company which enables them to sign in.

  - To add a new interviewer, press 'Register Interviewer'.

    When new interviewers have signed up with the name of your company, they will
    show up in that list.

    This will approve them to represent your company which enables them to sign in.

  - 'Post Announcement' let you message your employees. All coordinators and
    interviewers under your company will receive your announcement in their mailbox.

    You can either input from text field or upload a txt file.
