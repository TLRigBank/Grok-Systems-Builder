# Grok Systems Builder – User Stories

Extracted from the product specification document (`Grok Systems Builder.docx`).

These user stories define the required behavior for the web interface across public, learner, and admin surfaces.

---

## Landing Page (Visitor)

### US-1.1 -- View Value Proposition

**As a** visitor

**I want** to clearly understand what the Grok Systems Builder is and the main benefit it offers

**So that** I can quickly decide if it is relevant to me.

**Acceptance Criteria:**

• Hero section displays a clear headline and short supporting subheadline.

• Primary call-to-action button ("Start Free Path") is prominently visible above the fold.

• The page loads without requiring login.

---

### US-1.2 -- Understand How the Program Works

**As a** visitor

**I want** to see a simple explanation of the learning process

**So that** I know what to expect before signing up.

**Acceptance Criteria:**

• A "How it works" section shows 3--4 clear sequential steps.

• Each step is presented as a simple card or numbered item.

• The section is visible without excessive scrolling on a standard desktop view.

---

### US-1.3 -- Preview the Learning Path

**As a** visitor

**I want** to see an overview of the modules included in the program

**So that** I can evaluate the scope and relevance of the content.

**Acceptance Criteria:**

• Six module preview cards are displayed.

• Each card shows a module number/title and a short description.

• Cards are visually distinct and easy to scan.

---

### US-1.4 -- Compare Free vs Verified Options

**As a** visitor

**I want** to understand the difference between the free learning path and the verified/paid option

**So that** I can make an informed decision about enrollment.

**Acceptance Criteria:**

• A clear comparison section (table or side-by-side cards) shows what is included in Free vs Verified.

• Key differences (badge, portfolio review, gallery listing, etc.) are highlighted.

• The section supports the freemium model decision.

---

### US-1.5 -- See Social Proof via Example Portfolios

**As a** visitor

**I want** to view real examples of completed student portfolios

**So that** I can assess the quality and credibility of the program.

**Acceptance Criteria:**

• At least 2--3 example portfolio cards are shown.

• Each card links to the Public Portfolio Gallery or an individual project.

• Cards include basic information (title, short description, link).

---

### US-1.6 -- Start the Free Path

**As a** visitor

**I want** to begin the free learning experience with one clear action

**So that** I can start learning with minimal friction.

**Acceptance Criteria:**

• Primary CTA button ("Start Free Path") is present in the hero and repeated near the bottom.

• Clicking the CTA routes the user to the Sign Up page (or Login if already registered).

• No payment or complex form is required to begin.

---

### US-1.7 -- Navigate to Other Public Pages

**As a** visitor

**I want** easy access to the Portfolio Gallery and other key public pages

**So that** I can explore more information before committing.

**Acceptance Criteria:**

• Top navigation includes links to Portfolio Gallery and relevant pages.

• Footer contains basic links (About, How it works, etc.).

• All public links work without authentication.

---

## Sign Up / Login

### US-2.1 -- Create a New Account

**As a** visitor

**I want** to create an account quickly

**So that** I can begin the free learning path.

**Acceptance Criteria:**

• Sign-up form accepts email and password (or magic link).

• Successful sign-up creates an account and logs the user in.

• User is redirected to the Dashboard (or a short onboarding step) with Module 0 unlocked.

---

### US-2.2 -- Log In to an Existing Account

**As a** returning user

**I want** to log in with my credentials

**So that** I can resume my progress.

**Acceptance Criteria:**

• Login form accepts email and password (or magic link).

• Successful login restores the user session.

• After login, the user is taken to the Dashboard showing their current progress.

---

### US-2.3 -- Switch Between Sign Up and Login

**As a** visitor

**I want** to easily switch between the sign-up and login forms

**So that** I can use the correct flow without friction.

**Acceptance Criteria:**

• Clear toggle or links exist between Sign Up and Login views.

• Switching does not lose previously entered data where practical.

---

### US-2.4 -- Handle Form Validation and Errors

**As a** user

**I want** clear feedback when my credentials are invalid or incomplete

**So that** I can correct mistakes and succeed.

**Acceptance Criteria:**

• Required fields are validated.

• Invalid credentials or existing email produce clear error messages.

• Errors do not expose sensitive information.

---

### US-2.5 -- Begin Learning Immediately After Authentication

**As a** newly authenticated user

**I want** to land directly in the learning experience

**So that** there is no dead time after sign-up or login.

**Acceptance Criteria:**

• After successful sign-up or login, the user lands on the Dashboard.

• Module 0 is unlocked and available for new users.

---

## Public Portfolio Gallery

### US-3.1 -- Browse Approved Portfolios

**As a** visitor or learner

**I want** to view a gallery of real student portfolios that have been approved

**So that** I can assess the quality of work produced by the path.

**Acceptance Criteria:**

• Only portfolios that have passed review are displayed.

• Portfolios are shown in a clean grid of cards.

• Each card includes a title, short description, and basic visual placeholder or screenshot area.

---

### US-3.2 -- Filter or Scan Portfolios Easily

**As a** visitor

**I want** to scan or filter the gallery

**So that** I can find relevant examples quickly.

**Acceptance Criteria:**

• Basic filtering or clear visual scanning is supported.

• The layout remains usable as the number of portfolios grows.

---

### US-3.3 -- Open an Individual Portfolio

**As a** visitor

**I want** to click a portfolio card and view the actual project

**So that** I can examine the work in more detail.

**Acceptance Criteria:**

• Clicking a card opens the portfolio (repo link, demo, or detail view).

• External links open in a new tab where appropriate.

---

### US-3.4 -- Understand These Are Verified Completions

**As a** visitor

**I want** to know that the showcased portfolios represent successfully completed and reviewed work

**So that** I trust the social proof.

**Acceptance Criteria:**

• The page title or introductory text indicates these are approved / verified portfolios.

---

### US-3.5 -- View My Own Portfolio Listing (if approved)

**As a** learner whose portfolio has been approved and who opted in

**I want** to see my portfolio listed in the public gallery

**So that** I can share it and gain visibility.

**Acceptance Criteria:**

• Once a portfolio is approved and the user has opted in, it appears in the gallery.

---

### US-3.6 -- Navigate Back to Key Public Pages

**As a** visitor

**I want** easy navigation back to the home page and other public sections

**So that** I can continue exploring.

**Acceptance Criteria:**

• Standard navigation is available from the gallery page.

---

## Dashboard (Learner)

### US-4.1 -- See Overall Progress at a Glance

**As a** learner

**I want** to immediately see my overall progress in the program

**So that** I know how far I have come and how much remains.

**Acceptance Criteria:**

• A clear progress bar or percentage is displayed near the top of the Dashboard.

• The current module is visually highlighted.

• Progress updates in real time based on completed lessons and modules.

---

### US-4.2 -- Quickly Resume Learning

**As a** learner

**I want** a prominent "Continue" action that takes me exactly where I left off

**So that** I can resume with one click and minimal friction.

**Acceptance Criteria:**

• A large, primary "Continue Learning" (or similar) button is visible.

• Clicking it deep-links to the next incomplete lesson or the current Module Checkpoint.

• The button reflects the correct next step based on the user's saved progress.

---

### US-4.3 -- View Status of All Modules

**As a** learner

**I want** to see the status of every module (Locked, In Progress, Complete)

**So that** I understand the full path and what is currently available to me.

**Acceptance Criteria:**

• All six modules are listed with clear status indicators.

• Completed modules show a visual checkmark and artifact indicator.

• Locked modules are visually distinct and not clickable.

• In-progress modules are clearly marked.

---

### US-4.4 -- See Artifact and Feedback Status

**As a** learner

**I want** to know whether I have successfully uploaded the required artifact and submitted feedback for completed modules

**So that** I can confirm my module completions are properly recorded.

**Acceptance Criteria:**

• Completed modules display an indicator that an artifact has been uploaded.

• Feedback submission status is visible where relevant.

• Missing artifacts on otherwise completed lessons are clearly flagged if they block progress.

---

### US-4.5 -- Access the Portfolio Section When Eligible

**As a** learner who has completed all modules

**I want** easy access to the Portfolio Submission area from the Dashboard

**So that** I can proceed to the final capstone without hunting for it.

**Acceptance Criteria:**

• A clear link or card for Portfolio appears once all modules are complete.

• Before completion, the Portfolio section is either hidden or shown as locked with an explanation.

---

### US-4.6 -- Navigate to Other Key Areas

**As a** learner

**I want** simple navigation from the Dashboard to the Learning Path, Account Settings, and other core sections

**So that** I can move freely within the authenticated experience.

**Acceptance Criteria:**

• Sidebar or top navigation includes links to Learning Path, Portfolio (when available), and Account.

• Navigation is consistent and always accessible from the Dashboard.

---

## Learning Path (Modules Overview)

### US-5.1 -- View the Full Learning Path

**As a** learner

**I want** to see all six modules in sequence on one page

**So that** I understand the complete structure of the program and my position within it.

**Acceptance Criteria:**

• All six modules are displayed in order.

• Each module card shows the module number, title, and a short description.

• The layout makes the sequential nature of the path clear.

---

### US-5.2 -- See Clear Status for Every Module

**As a** learner

**I want** each module to display an accurate status (Locked, In Progress, or Complete)

**So that** I know what I can access right now and what I have already finished.

**Acceptance Criteria:**

• Locked modules are visually distinct and not clickable.

• In-progress modules are clearly marked.

• Completed modules show a checkmark or equivalent completion indicator.

• Status reflects real-time progress data from the user's account.

---

### US-5.3 -- Access Only Unlocked Modules

**As a** learner

**I want** to open only the modules that are currently unlocked

**So that** the sequential learning design is enforced.

**Acceptance Criteria:**

• Clicking an unlocked module takes the user into that module's lessons or checkpoint.

• Clicking a locked module does nothing or shows a brief message explaining it is locked.

---

### US-5.4 -- View Artifact Status on Completed Modules

**As a** learner

**I want** to see whether the required artifact for a completed module has been submitted

**So that** I have confidence my progress is fully recorded.

**Acceptance Criteria:**

• Completed modules show an artifact status indicator.

---

### US-5.5 -- Navigate into a Module or Back to Dashboard

**As a** learner

**I want** clear ways to enter a module and return to the Dashboard

**So that** navigation feels natural.

**Acceptance Criteria:**

• Module cards or titles are clickable when unlocked.

• A consistent way back to the Dashboard is always available.

---

## Lesson View

### US-6.1 -- View Lesson Content

**As a** learner

**I want** to read the lesson content clearly

**So that** I can learn the material.

**Acceptance Criteria:**

• Lesson title, body content, and any embedded resources are displayed.

• Content is readable on desktop and mobile viewports.

---

### US-6.2 -- Complete Practical Actions in the Lesson

**As a** learner

**I want** to perform the practical steps described in the lesson

**So that** I build real skill rather than only reading.

**Acceptance Criteria:**

• Lessons that require external actions (e.g., running Grok Build) provide clear instructions.

• The interface does not block the learner from leaving to perform those actions.

---

### US-6.3 -- Mark a Lesson as Complete

**As a** learner

**I want** to mark a lesson complete when I have finished it

**So that** my progress is recorded.

**Acceptance Criteria:**

• A clear "Mark Complete" or equivalent action exists.

• Completing a lesson updates progress and may unlock the next lesson.

---

### US-6.4 -- Navigate Between Lessons and Back to the Module

**As a** learner

**I want** to move between lessons within a module and return to the module overview

**So that** I can control my learning pace.

**Acceptance Criteria:**

• Previous / Next lesson navigation is available where applicable.

• A link back to the module or Learning Path is present.

---

### US-6.5 -- See Context of Current Position

**As a** learner

**I want** to know which module and lesson I am currently in

**So that** I maintain orientation.

**Acceptance Criteria:**

• Breadcrumb or equivalent context is shown (Module X > Lesson Y).

---

## Module Checkpoint (Artifact + Feedback)

### US-7.1 -- Understand the Required Artifact

**As a** learner

**I want** to clearly understand what artifact is required to complete the module

**So that** I know what to produce.

**Acceptance Criteria:**

• The required artifact is described in plain language.

• Any format or quality expectations are stated.

---

### US-7.2 -- Upload an Artifact

**As a** learner

**I want** to submit my artifact via URL, file upload, or both

**So that** I can complete the module with evidence of my work.

**Acceptance Criteria:**

• A URL input field is available.

• An optional file upload area is available.

• A notes / Architecture Decision Record text area is provided.

• The user can submit using URL only, file only, or both.

• Uploaded data is saved and permanently linked to the user and the specific module.

---

### US-7.3 -- Provide Module Feedback

**As a** learner

**I want** to give feedback on the module (rating + written comments)

**So that** the team can improve the learning experience based on real input.

**Acceptance Criteria:**

• A simple rating control (e.g., 1--5 stars or equivalent) is present.

• A free-text feedback field is available.

• Feedback is required (or strongly enforced) as part of module completion.

• Submitted feedback is stored and associated with the user and module.

---

### US-7.4 -- Submit and Complete the Module

**As a** learner

**I want** to submit my artifact and feedback in one action and have the module marked complete

**So that** I can unlock the next module and continue progressing.

**Acceptance Criteria:**

• A primary "Submit & Complete Module" button is present.

• Successful submission saves the artifact and feedback, marks the module complete, unlocks the next module, updates overall progress, and redirects with confirmation.

• The system prevents completion if required elements are missing.

---

### US-7.5 -- Receive Validation and Error Feedback

**As a** learner

**I want** clear validation messages if my submission is incomplete or invalid

**So that** I can correct issues and successfully complete the module.

**Acceptance Criteria:**

• The system requires at least one artifact (URL or file) and feedback before allowing submission.

• Missing required fields trigger clear, specific error messages.

• Invalid URL formats and file upload errors are communicated clearly.

---

### US-7.6 -- Review Previously Submitted Artifact (if returning)

**As a** learner who has already completed the module

**I want** to view the artifact and feedback I previously submitted

**So that** I can reference my past work.

**Acceptance Criteria:**

• If the module is already complete, the page shows the existing submission in a read-only or editable state (depending on final rules).

---

## Portfolio Submission

### US-8.1 -- Access the Portfolio Submission Page Only When Eligible

**As a** learner

**I want** the portfolio submission page to be available only after I have completed all required modules

**So that** the sequential design of the path is preserved.

**Acceptance Criteria:**

• The page is accessible only when all modules are complete.

• Attempting to access it earlier shows a clear explanation of remaining requirements.

---

### US-8.2 -- Submit the Required Portfolio Materials

**As a** learner

**I want** to submit my final portfolio materials (repo, demo, ADR, notes)

**So that** I can request verification.

**Acceptance Criteria:**

• Fields exist for repository URL, optional demo URL, Architecture Decision Record, and additional notes.

• File upload is supported where relevant.

• All required fields are validated before submission.

---

### US-8.3 -- Submit for Review

**As a** learner

**I want** to submit my portfolio for human review

**So that** I can earn the Verified credential.

**Acceptance Criteria:**

• A clear "Submit for Review" action exists.

• Successful submission changes status to "Pending Review" and notifies the review queue.

---

### US-8.4 -- Track Submission Status

**As a** learner

**I want** to see the current status of my portfolio submission

**So that** I know whether it is pending, approved, or needs revision.

**Acceptance Criteria:**

• Status is clearly displayed (Pending, Approved, Needs Revision).

---

### US-8.5 -- Resubmit After Revision Request

**As a** learner whose portfolio was returned for revision

**I want** to update my materials and resubmit

**So that** I can still earn the credential.

**Acceptance Criteria:**

• The learner can edit and resubmit after a revision request.

• Previous feedback remains visible.

---

### US-8.6 -- Receive Clear Validation and Error Handling

**As a** learner

**I want** clear validation when my portfolio submission is incomplete

**So that** I can fix issues before it enters the review queue.

**Acceptance Criteria:**

• Required fields are enforced.

• Helpful error messages are shown.

---

## Completion / Certificate Page

### US-9.1 -- Access the Completion Page Only After Approval

**As a** learner

**I want** the completion / certificate page to appear only after my portfolio has been approved

**So that** it remains a meaningful milestone.

**Acceptance Criteria:**

• The page is gated behind an approved portfolio status.

---

### US-9.2 -- View and Celebrate My Achievement

**As a** verified learner

**I want** a clear celebration of my completion

**So that** the achievement feels real.

**Acceptance Criteria:**

• Badge or credential is prominently displayed.

• Congratulatory messaging is present.

---

### US-9.3 -- Download My Certificate

**As a** verified learner

**I want** to download a certificate or credential artifact

**So that** I can keep or share proof of completion.

**Acceptance Criteria:**

• A download action is available for the certificate.

---

### US-9.4 -- Share My Achievement

**As a** verified learner

**I want** easy ways to share my achievement

**So that** I can signal it on professional networks.

**Acceptance Criteria:**

• Share options (or copyable links) are provided.

---

### US-9.5 -- View My Public Gallery Listing

**As a** verified learner who opted into the public gallery

**I want** a direct link to my gallery listing

**So that** I can share it.

**Acceptance Criteria:**

• A link to the public gallery entry is present when applicable.

---

### US-9.6 -- Discover Logical Next Steps

**As a** verified learner

**I want** suggestions for what to do next

**So that** the experience does not end abruptly.

**Acceptance Criteria:**

• "What's next" suggestions are shown (further projects, community, related paths, etc.).

---

## Account Settings

### US-10.1 -- View and Update Basic Profile Information

**As a** learner

**I want** to view and update my basic profile information

**So that** my account stays accurate.

**Acceptance Criteria:**

• Name, email, and other basic fields are editable.

• Changes are saved successfully.

---

### US-10.2 -- Change Password (or Manage Authentication)

**As a** learner

**I want** to change my password or manage authentication methods

**So that** I can keep my account secure.

**Acceptance Criteria:**

• Password change (or equivalent auth management) is available.

---

### US-10.3 -- View History of My Uploaded Artifacts

**As a** learner

**I want** to see a history of the artifacts I have submitted

**So that** I can reference my past work.

**Acceptance Criteria:**

• A list or history of uploaded artifacts is available.

---

### US-10.4 -- Access or Export My Data

**As a** learner

**I want** to access or export my account data

**So that** I retain ownership of my information.

**Acceptance Criteria:**

• A data access or export option is provided.

---

### US-10.5 -- Request Account Deletion

**As a** learner

**I want** to request deletion of my account

**So that** I can remove my data if desired.

**Acceptance Criteria:**

• An account deletion request flow exists.

---

### US-10.6 -- Navigate Safely Within Account Settings

**As a** learner

**I want** clear navigation within account settings and back to the main app

**So that** I do not get lost.

**Acceptance Criteria:**

• Consistent navigation is available from the settings area.

---

## Admin Dashboard / Analytics

### US-11.1 -- View Key Performance Metrics at a Glance

**As an** admin

**I want** to see the most important platform metrics in one place

**So that** I can understand the health of the path.

**Acceptance Criteria:**

• Key metrics (sign-ups, module completion, portfolio submissions, approval rate, etc.) are displayed.

---

### US-11.2 -- Understand User Progression with Simple Visuals

**As an** admin

**I want** simple visuals of how learners are progressing

**So that** I can spot drop-off points.

**Acceptance Criteria:**

• Progression or funnel-style visuals are available.

---

### US-11.3 -- Review Recent Platform Activity

**As an** admin

**I want** a view of recent activity

**So that** I stay aware of what is happening on the platform.

**Acceptance Criteria:**

• Recent sign-ups, submissions, and reviews are visible.

---

### US-11.4 -- Filter Analytics by Date Range

**As an** admin

**I want** to filter metrics by date range

**So that** I can analyze specific periods.

**Acceptance Criteria:**

• Date range filtering is supported.

---

### US-11.5 -- Access Deeper Admin Views from the Dashboard

**As an** admin

**I want** quick links to the review queue and user detail tools

**So that** I can move into operational work efficiently.

**Acceptance Criteria:**

• Clear navigation to the Portfolio Review Queue and user management is present.

---

### US-11.6 -- Trust the Data Source

**As an** admin

**I want** the metrics to be accurate and up to date

**So that** I can make decisions based on them.

**Acceptance Criteria:**

• Data reflects the current state of the system within a reasonable refresh window.

---

## Admin – User Detail View

### US-12.1 -- View a Learner's Summary Information

**As an** admin

**I want** a summary of a learner's account and progress

**So that** I can quickly understand their status.

**Acceptance Criteria:**

• Key identity and progress information is displayed.

---

### US-12.2 -- Inspect the Complete Activity Timeline

**As an** admin

**I want** to see the full timeline of a learner's activity

**So that** I can support them or investigate issues.

**Acceptance Criteria:**

• A chronological activity history is available.

---

### US-12.3 -- Review All Artifact Uploads

**As an** admin

**I want** to inspect every artifact a learner has submitted

**So that** I have full context for portfolio review or support.

**Acceptance Criteria:**

• All module artifacts are listed and accessible.

---

### US-12.4 -- Read All Feedback Submitted by the User

**As an** admin

**I want** to read the feedback a learner has given on modules

**So that** I can improve the path and understand their experience.

**Acceptance Criteria:**

• Module feedback is viewable.

---

### US-12.5 -- Support Analysis and User Assistance

**As an** admin

**I want** enough context on a user detail page to provide meaningful help

**So that** support interactions are efficient.

**Acceptance Criteria:**

• The page aggregates the information needed for common support and review tasks.

---

### US-12.6 -- Navigate to and from the User Detail View

**As an** admin

**I want** easy navigation to and from the user detail view

**So that** I can move between tools without friction.

**Acceptance Criteria:**

• Clear paths exist back to the Admin Dashboard and Review Queue.

---

## Admin – Portfolio Review Queue

### US-13.1 -- View All Pending Portfolio Submissions

**As an** admin

**I want** to see every portfolio currently awaiting review

**So that** I can manage the review workload.

**Acceptance Criteria:**

• All pending submissions are listed.

• Key metadata (learner, submission date, status) is visible.

---

### US-13.2 -- Access Supporting Context for a Submission

**As an** admin

**I want** quick access to the user's earlier module artifacts and history while reviewing a portfolio

**So that** I can make a well-informed approval decision.

**Acceptance Criteria:**

• Each queue item provides easy access to the user's detail view or directly to their previous artifacts.

• Repository and any live demo links are clickable.

• Architecture Decision Record content is viewable without leaving the review context where practical.

---

### US-13.3 -- Approve a Portfolio

**As an** admin

**I want** to approve a completed portfolio

**So that** the learner can receive their badge and optional public gallery listing.

**Acceptance Criteria:**

• An "Approve" action is available for each pending submission.

• Approving a portfolio updates its status to "Approved."

• The system issues the completion badge / credential.

• The portfolio can be added to the Public Portfolio Gallery if the user opted in.

• The action is logged.

---

### US-13.4 -- Request Revisions on a Portfolio

**As an** admin

**I want** to return a portfolio to the learner with feedback when it does not yet meet the standard

**So that** the learner can improve and resubmit.

**Acceptance Criteria:**

• A "Request Revision" (or equivalent) action is available.

• The admin can provide written feedback explaining what needs to change.

• The portfolio status updates to "Needs Revision."

• The learner is able to see the feedback and resubmit.

• The action is logged.

---

### US-13.5 -- Track Review Actions and History

**As an** admin

**I want** a record of review decisions and notes

**So that** there is accountability and continuity if multiple admins are involved.

**Acceptance Criteria:**

• Approve and Request Revision actions are recorded with timestamp and admin identity (where applicable).

• Previous review notes remain accessible.

• The queue reflects the latest status of each submission accurately.

---

### US-13.6 -- Navigate Efficiently Within Admin Tools

**As an** admin

**I want** seamless navigation between the Portfolio Review Queue, User Detail views, and the main Admin Dashboard

**So that** I can complete reviews without friction.

**Acceptance Criteria:**

• Clear navigation exists to the Admin Dashboard and to individual User Detail pages.

• Returning to the queue preserves context where possible.

• The review workflow feels connected to the rest of the admin experience.

---
