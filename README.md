[View](https://antosx44.github.io/fcbportfolio/)


# CEP-ONHS: Pre-Final Defense Presentation Script (Taglish Version)
### Centralized E-Learning Platform — Olea National High School
#### School Year 2025–2026

---

## TIMING GUIDE

| Section | Time Budget | Cumulative |
|---------|-----------|------------|
| 1. Opening & Introduction | 2 min | 0:00 – 2:00 |
| 2. System Overview & Problem Statement | 2 min | 2:00 – 4:00 |
| 3. Landing Page & Login | 1 min | 4:00 – 5:00 |
| 4. Admin Module Walkthrough | 5 min | 5:00 – 10:00 |
| 5. Teacher Module Walkthrough | 4 min | 10:00 – 14:00 |
| 6. Student Module Walkthrough | 3 min | 14:00 – 17:00 |
| 7. Technical Architecture & Security | 1.5 min | 17:00 – 18:30 |
| 8. Summary & Closing | 1.5 min | 18:30 – 20:00 |
| **Q&A** | **10 min** | **20:00 – 30:00** |

> **Tip:** Mag-assign ng isang teammate bilang **timekeeper** na mag-signal sa inyo kapag malapit na sa limit ng bawat section.

---

> **STAGE DIRECTIONS:**
> - **(CLICK)** = I-advance ang slide / mag-navigate sa next page ng live demo
> - **(PAUSE)** = Sandaling huminto ng 2–3 seconds para sa emphasis
> - **(GESTURE)** = Ituro ang screen / projected display
> - **[SPEAKER]** = Sino ang nagsasalita sa parteng iyon

---

## 1. OPENING & INTRODUCTION ⏱️ 0:00 – 2:00
**[SPEAKER 1 — Lead Presenter]**

> Magandang [umaga/hapon] po sa ating mga panelist, sa ating respected adviser, at sa ating mga kapwa estudyante.

> Kami po ang **[Team Name / Group Number]**, at ngayong araw, ipre-present po namin ang aming capstone project — **(PAUSE)** — ang **Centralized E-Learning Platform for Olea National High School**, o ang tinatawag naming **CEP-ONHS**.

> Bago po ang lahat, may tanong lang po kami. **(PAUSE)**

> Sa isang school na may daan-daang students mula Grade 7 hanggang 10, dose-dosenang teachers, at isang administration na nag-o-oversee sa lahat — paano natin mase-ensure na **connected**, **organized**, at **naka-align** ang lahat?

> Ang tanong na iyan — **(PAUSE)** — ang eksaktong sinasagot ng system na ito.

> Ang CEP-ONHS ay isang **complete, web-based Learning Management System** para sa Filipino junior high school setting. Pinagsasama-sama nito ang **tatlong core user roles** — Administrator, Teacher, at Student — sa isang centralized na platform.

> Lessons online, assignments digital, quizzes auto-graded, announcements instant, at school operations — lahat sa isang dashboard lang.

> Ngayong araw, magde-demo po kami ng system — module by module. Simulan na po natin. **(CLICK)**

---

## 2. SYSTEM OVERVIEW & PROBLEM STATEMENT ⏱️ 2:00 – 4:00
**[SPEAKER 1 — Lead Presenter]**

> **Ang Problema:**
> Sa traditional na public high school setup, fragmented ang tools — paper-based ang lesson plans, manual ang grades, bulletin board ang announcements, at pisikal ang assignments. Resulta? **Delays, data silos, at communication gaps.**

> **Ang Solusyon:**
> Isang **unified web platform** kung saan:
> - Mina-manage ng **Admin** ang users, classes, subjects, at settings.
> - Gumagawa ang **Teachers** ng lessons, assignments, at quizzes — at nag-gre-grade.
> - Ina-access ng **Students** ang lahat ng content at nakakatanggap ng real-time notifications.

> **Tech Stack:**
> Ang system ay built sa:
> - **PHP 8.2** — clean procedural code, **zero framework bloat**
> - **MySQL/MariaDB** — **17 tables** na relational database
> - **HTML5, CSS3, Vanilla JavaScript** — walang heavy JS frameworks, mabilis ang page loads
> - **PHPMailer** para sa email, **HTMLPurifier** para sa security
> - Naka-host sa **Apache/XAMPP** na may `.htaccess` hardening

> Sa kabuuan: **160+ PHP files**, tatlong dedicated portals. Ipapakita na po namin. **(CLICK)**

---

## 3. LIVE DEMO: LANDING PAGE & LOGIN ⏱️ 4:00 – 5:00
**[SPEAKER 1 — Lead Presenter]**

> **(GESTURE)** Ito po ang aming **Landing Page** — ang unang makikita ng user.

> Clean at modern ang design. Ang tagline: **"Your Gateway to Smarter Learning."** Malinaw na kino-communicate kung ano ang system.

> Pag nag-scroll tayo pababa **(CLICK)**, tatlong **Portal Selection** — Student, Teacher, at Administrator. May **Features Overview** at **FAQ** section din.

> Mag-log in na po tayo sa **Admin account**. **(CLICK)**

---

## 4. ADMIN MODULE WALKTHROUGH ⏱️ 5:00 – 10:00
**[SPEAKER 2 — Admin Module Presenter]**

> Salamat, [Speaker 1 name]. Ako na po ang magde-demo ng **Admin Module**.

### 4.1 Admin Login ⏱️ ~5:00

> Nandito po tayo sa Admin Login. **(GESTURE)** Bawat form sa system ay may **CSRF token validation**, ang passwords ay hina-hash gamit **bcrypt**, at ang login ay **rate-limited** kontra brute-force. Mag-log in na po tayo. **(CLICK)**

### 4.2 Admin Dashboard ⏱️ ~5:30

> **(PAUSE)** Ito po ang **Admin Dashboard** — ang command center ng CEP-ONHS.

> **(GESTURE)** Sa taas: **quick-stat cards** — total students, teachers, classes, at subjects. Nag-a-update ito sa **real-time**.

> Sa baba: **visual analytics** — Grade Distribution Chart, Department-wise Teacher Distribution, at Student Status Summary kung ilan ang enrolled versus dropped.

> Sa kanan: **Recent Student Registrations** at **Recent Announcements** — para agad makita ng admin ang latest activity.

> Isang tingin lang — alam mo na ang estado ng buong school.

### 4.3 Student & Teacher Management ⏱️ ~6:30

> Punta tayo sa **Student Management**. **(CLICK)**

> **(GESTURE)** Lahat ng registered students — paginated table na may **LRN, name, grade level, section, email, at status**. Puwedeng mag-filter — **(CLICK)** — demo ko, Grade 10. Agad nag-update.

> Puwedeng **mag-add, edit, view profile, at delete** ng students — lahat may confirmation prompts.

> Sa **Teacher Management** **(CLICK)** — pareho ang features, pero may bonus: **auto-generated Employee ID** sa format na **T-YYYY-NNN** — halimbawa, T-2025-001. Automatic at unique, walang manual input needed.

### 4.4 Class & Subject Management ⏱️ ~7:30

> Sa **Class Management** **(CLICK)** — dito nag-o-organize ng class structure. Bawat class ay naka-link sa subject, teacher, grade level, at schedule.

> Pinaka-proud kami dito: ang **Advisory Class System**. **(PAUSE)** Dito sa Pilipinas, ang sections ay Rizal, Mabini, Luna — natively sine-support namin ito, na may **gold gradient header** para ma-distinguish ang advisory mula sa regular classes. **(GESTURE)**

> Sa **Subject Management** **(CLICK)** — subjects per grade level na may code (MATH7, SCI8), at drill-down sa content per subject.

### 4.5 Lesson Builder & Announcements ⏱️ ~8:15

> Ang admin ay puwedeng **mag-add ng lessons directly**. **(CLICK)** **(GESTURE)** May **rich text editor**, **YouTube/Vimeo embed**, **PDF upload** (10MB limit), **quarter/week organization**, at **publish/draft toggle**.

> Sa **Announcements** **(CLICK)** — ito po ang isa sa pinaka-powerful features. May **type** (General, Academic, Event, System), **audience selector** (All, Students, Teachers, Specific Class), **priority level** (Normal, Important, Urgent), at — pinaka-key — optional na **email broadcast**. Kahit hindi naka-log in ang user, matatanggap niya sa email.

### 4.6 System Settings ⏱️ ~9:00

> Panghuli sa admin — ang **System Settings**. **(CLICK)** **(GESTURE)** Lahat configurable sa UI — **walang code changes needed**:

> - **Maintenance mode** na may custom message
> - **Registration toggle** — on/off para sa students at teachers
> - **Password policy** — default password at minimum length
> - **File upload limits** at **session timeout**
> - **Full SMTP setup** — compatible sa Gmail, Office 365, kahit anong mail server
> - **Notification settings** — reminder hours, polling interval, auto-delete age
> - **CSV data export** para sa reporting

> At ang **Notification Center** — real-time notifications na may filter, mark-as-read, at auto-refresh na bell dropdown sa bawat page.

> Iyan po ang Admin Module — **full control** sa buong institution. Ibibigay ko na po kay **[Speaker 3 name]** para sa Teacher Module. **(CLICK)**

---

## 5. TEACHER MODULE WALKTHROUGH ⏱️ 10:00 – 14:00
**[SPEAKER 3 — Teacher Module Presenter]**

> Salamat, [Speaker 2 name]. Pumasok na tayo sa perspektibo ng **teacher**.

### 5.1 Teacher Dashboard ⏱️ ~10:15

> Mag-log in tayo sa teacher account. **(CLICK)**

> **(PAUSE)** Ito ang **Teacher Dashboard**. **(GESTURE)** May **personalized greeting** base sa oras — "Good Morning" o "Good Afternoon." Tapos:
> - **Today's Schedule** — mga classes para sa araw na ito
> - **Quick Stats** — total classes, students, active assignments, at **pending submissions**
> - **Recent Submissions** — 8 pinaka-latest, para agad makapagsimulang mag-grade

> Pagka-log in, alam na ng teacher kung **ano ang kailangang gawin**.

### 5.2 My Classes ⏱️ ~10:45

> Sa **My Classes** **(CLICK)** — dalawang category:
> 1. **Advisory Classes** — may gold gradient header para agad ma-distinguish
> 2. **Subject Classes** — organized by grade level na may schedule at student count

> Pag nag-click sa class, bubukas ang dedicated page para sa lessons, assignments, quizzes, at enrollees.

### 5.3 Lesson Creation ⏱️ ~11:15

> Ide-demo ko ang **paggawa ng lesson**. **(CLICK)** **(GESTURE)**

> - **Title** at **Summary** para sa lesson card
> - **Rich text editor** — bold, italic, headings, lists — hindi ordinary text box
> - **Video Link** — YouTube o Vimeo URL, automatic na nag-e-embed — students nanonood directly sa platform
> - **PDF Attachment** — hanggang 10MB
> - **Quarter & Week** — aligned sa academic calendar
> - **Publish o Draft** — save muna bago i-publish

> Gumawa ako ng sample lesson. **(DEMONSTRATE)** Naka-publish na — agad visible sa enrolled students. **(PAUSE)**

### 5.4 Assignment & Grading ⏱️ ~12:00

> Sa **Assignments** **(CLICK)** — straightforward lang:
> - Title, description, instructions, file attachment
> - **Due date** via date-time picker
> - **Late submission policy** — allow o disallow
> - **Resubmission** — kung gusto, puwedeng mag-revise ang students
> - Grading category at publish/draft workflow

> Kapag may submissions na **(CLICK)**, ito ang **grading view**: **(GESTURE)**
> - **Download** ng student file
> - **Score entry** kasama ang max score
> - **Detailed feedback** sa rich text
> - **Upload annotated version** — i-markup at ibalik sa student
> - **Filter** by status — submitted, graded, o late

### 5.5 Quiz Builder ⏱️ ~12:45

> Ngayon, ang paborito kong feature — ang **Quiz Builder**. **(CLICK)**

> **(GESTURE)** Tatlong question types:
> 1. **Multiple Choice** — custom options, isang correct answer
> 2. **True or False**
> 3. **Short Answer** — open-ended

> Mga powerful na options:
> - **Question shuffling** — random ang order per student
> - **Option shuffling** — random din ang choices
> - **Time limit** — countdown timer habang kumukuha
> - Total points, due date, publish/draft

> I-demo ko — **(DEMONSTRATE QUIZ CREATION)**

> At ang pinaka-highlight: **auto-grading engine**. **(PAUSE)** Para sa Multiple Choice at True/False, ang system ay **agad nagge-grade pagka-submit**. Instant results. Para sa Short Answer, manual ang grading ng teacher.

> Puwede ring **tingnan ang detailed results** — bawat student, bawat question, kasama ang correct answers.

### 5.6 Teacher Announcements & Profile ⏱️ ~13:30

> Teachers may sarili ring **announcement system** **(CLICK)** — puwedeng i-target ang specific class lang, students only, o everyone. May email notification option din.

> At syempre, may **Profile page** at **Notification Center** — real-time, may filter, at may bell dropdown.

> Iyan po ang Teacher Module — isang **complete digital teaching toolkit**. Si **[Speaker 4 name]** naman po para sa Student experience. **(CLICK)**

---

## 6. STUDENT MODULE WALKTHROUGH ⏱️ 14:00 – 17:00
**[SPEAKER 4 — Student Module Presenter]**

> Salamat, [Speaker 3 name]. Ngayon ang pinaka-importanteng perspektibo — ang **Student** — kasi para sa kanila talaga ang system na ito.

### 6.1 Student Dashboard ⏱️ ~14:15

> Mag-log in tayo. Students ginagamit ang kanilang **LRN** at password. **(CLICK)**

> **(PAUSE)** Ang **Student Dashboard**. **(GESTURE)**

> - **Announcement Carousel** — latest announcements na color-coded by priority
> - **Upcoming Assignments & Quizzes** — calendar-style view ng mga malapit nang mag-due
> - **Recently Visited Subjects** — smart feature ito — **tina-track ng system kung saan ka huling nag-aral**, at nilalagay sa unahan. Parang naalala ng platform kung saan ka huminto
> - **Subject Quick-Access Cards** — bawat enrolled subject, isang click lang

> Pagka-log in, sagot agad: **"Ano ang kailangan kong gawin ngayon?"**

### 6.2 Subjects & Lessons ⏱️ ~15:00

> Sa **My Subjects** **(CLICK)** — lahat ng enrolled subjects na may teacher name, schedule, at room.

> Pag nag-click ng subject **(CLICK)**, bubukas ang lessons, assignments, at quizzes.

> Ang **Lessons** **(GESTURE)** — organized by quarter at week:
> - Full rich-text content — gaya ng sinulat ng teacher
> - **Embedded videos** — YouTube/Vimeo, play directly, walang need lumipat ng tab
> - **Downloadable PDFs** — supplementary materials

> Parang dedicated na **digital textbook** ang dating.

### 6.3 Assignment Submission ⏱️ ~15:45

> Sa **Assignments** **(CLICK)** — makikita ng student ang title, instructions, due date, at submission status.

> Para mag-submit: click **"Submit Assignment"**, piliin ang file, tapos **Upload**. **(DEMONSTRATE)**

> Agad nag-update ang status. Kung may **resubmission**, puwedeng mag-revise at i-submit ulit.

> Pagka-grade, makikita ang **score**, ang **detailed feedback** ng teacher, at kung may **annotated file** — puwedeng i-download. **Complete feedback loop** — lahat sa platform.

### 6.4 Taking a Quiz ⏱️ ~16:15

> At ang paborito ng students — **Quiz Taking**. **(CLICK)**

> **(GESTURE)** Kapag nagsimula:
> - **Countdown timer** sa taas kung may time limit
> - **Shuffled questions at options** — iba-iba ang order per student, mahirap mag-copy
> - Multiple Choice, True/False, at Short Answer

> Sumagot tayo at mag-submit. **(DEMONSTRATE)**

> **(PAUSE)** At agad-agad — **instant results**. **(GESTURE)** Score, tama o mali bawat question, correct answers. Hindi na maghihintay ng days — malalaman mo **agad**.

### 6.5 Notifications & Profile ⏱️ ~16:40

> Ang students ay may **Announcement page** — filtered para relevant lang sa kanila. May **Notification Center** na nag-a-auto-refresh — new assignments, quiz results, at **due-date reminders** 24 hours before deadline.

> At **Student Profile** — update info at upload profile picture.

> Iyan po ang Student Module. Ibabalik ko po kay **[Speaker 1 name]**. **(CLICK)**

---

## 7. TECHNICAL ARCHITECTURE & SECURITY ⏱️ 17:00 – 18:30
**[SPEAKER 1 — Lead Presenter / or Speaker 2]**

> Salamat, [Speaker 4 name]. Bago tayo mag-close, ang system behind the scenes.

### 7.1 Architecture

> **17-table relational database** na may foreign keys at indexes. **160+ PHP files** across tatlong portals.

> Database schema: user tables (admins, teachers, students), academic tables (subjects, classes, enrollments), content tables (lessons, assignments, quizzes, submissions), communication tables (announcements, notifications), at system tables (settings, activity logs, visit tracking).

### 7.2 Security — 9.5/10 Audit Score, Zero Open Findings

> Ang security po ay **built-in mula sa simula**, hindi afterthought.

> **(GESTURE)** Walong key measures:
> 1. **SQL Injection Prevention** — 100% prepared statements, walang inline concatenation
> 2. **XSS Prevention** — HTMLPurifier at `htmlspecialchars` sa lahat ng output
> 3. **CSRF Protection** — token sa bawat form, validated gamit `hash_equals()`
> 4. **Password Security** — bcrypt hashing na may configurable policy
> 5. **Session Security** — HttpOnly, SameSite=Strict, Secure flag, 30-min regeneration
> 6. **Rate Limiting** — per-role limit sa login attempts
> 7. **Apache Hardening** — blocked access sa .env/.sql/.log, CSP headers, X-Frame-Options
> 8. **Role-Based Access Control** — bawat page at endpoint, verified ang role bago mag-grant ng access

### 7.3 Key Differentiators

> Tatlong bagay na nagpa-stand out ng CEP-ONHS:
> 1. **Zero framework, dalawang packages lang** (PHPMailer + HTMLPurifier) — lightweight, maliit na attack surface, madaling i-deploy sa school na may limited IT
> 2. **Filipino Context-Aware** — advisory class naming (Rizal, Mabini, Luna), DepEd-aligned na grading structure
> 3. **Fully configurable sa UI** — SMTP, notifications, registration, maintenance mode — lahat adjustable nang walang code changes

---

## 8. SUMMARY & CLOSING ⏱️ 18:30 – 20:00
**[SPEAKER 1 — Lead Presenter]**

> **(PAUSE)**

> Para i-summarize:

> **Para sa Admin** — **complete management console**: user CRUD, class at subject organization, announcements na may email broadcast, full system settings, data exports, at real-time analytics. **360-degree visibility** at **full control**.

> **Para sa Teacher** — **complete digital teaching toolkit**: rich lessons na may video at PDF, auto-graded quizzes na may shuffling, assignment grading na may detailed feedback. Focus sa **pagtuturo, hindi paperwork**.

> **Para sa Student** — **seamless learning experience**: lessons, assignments, quizzes na may instant feedback, at real-time notifications. Organized, accessible, at transparent ang buong academic journey.

> Lahat ng ito — **(PAUSE)** — isang login. Isang dashboard. Isang system.

> Ang CEP-ONHS ay hindi lang project — ito ay isang **gumaganang solusyon** para sa realities ng Filipino public education. **Secure** — 9.5/10 audit score. **Lightweight** — walang framework bloat. **Configurable** — no-code administration. At higit sa lahat — **inuuna nito ang learning experience**.

> Naniniwala po kami na ang technology ay dapat **magpasimple ng edukasyon, hindi magpahirap nito**. At iyan po ang nasa bawat page, bawat feature, at bawat linya ng code ng system na ito.

> **(PAUSE)**

> Handa na po kami sa inyong mga tanong at feedback.

> Maraming salamat po, at magandang [umaga/hapon] po sa inyong lahat. **(BOW / END)**

---

## ⏱️ Q&A SESSION — 20:00 – 30:00

> Ang panelist ay magtatanong. Gamitin ang reference table sa baba para sa mabilisang sagot.

| Possible na Tanong | Key Answer |
|-------------------|-----------|
| "Anong technology stack ang ginamit niyo?" | PHP 8.2, MySQL/MariaDB, HTML5/CSS3/Vanilla JS, Apache/XAMPP, PHPMailer, HTMLPurifier |
| "Bakit walang framework (Laravel, React)?" | Lightweight deployment, lower maintenance, mas madaling i-handoff sa school IT, fewer dependencies = smaller attack surface |
| "Paano niyo pinipigilan ang SQL injection?" | 100% prepared statements na may parameter binding. Zero inline concatenation |
| "Paano gumagana ang quiz auto-grading?" | MC at T/F answers kino-compare sa stored correct answers sa JSON; agad na scored pagka-submit |
| "Puwede bang mag-cheat ang students sa quizzes?" | Question shuffling + option shuffling + time limits ang nagmi-minimize ng cheating |
| "Paano gumagana ang real-time notifications?" | JavaScript polling sa configurable intervals (default 30s). Walang external service needed |
| "Paano dine-deploy ang system?" | XAMPP (Apache + MySQL), Composer install, SQL migration scripts, .env configuration |
| "Ano ang database structure?" | 17 tables — users, academics, content, communication, at system settings |
| "Paano niyo hina-handle ang file uploads nang secure?" | Size limits (configurable), type validation, .htaccess restrictions |
| "Kaya bang i-support ng system ang multiple schools?" | Currently single-school; multi-tenant puwedeng future enhancement |
| "Ilan ang concurrent users na kaya?" | Optimized para sa typical school (~500-1000 users) gamit indexed queries at pagination |
| "Kumusta ang mobile responsiveness?" | Responsive CSS; nag-a-adapt ang UI sa iba't ibang screen sizes |
| "Paano gumagana ang email integration?" | PHPMailer via SMTP; supports Gmail, Office 365, custom servers; configurable sa admin UI |
| "May activity log ba?" | Oo — activity_logs table, tracks admin actions na may timestamps |
| "Anong security audit score?" | 9.5 out of 10, zero open critical findings |

---

## PRACTICE TIPS

1. **Mag-rehearse na may timer** — i-practice nang 3x bago ang actual defense. Target: under 20 minutes.
2. **Mag-assign ng timekeeper** — isang teammate na mag-signal ng "5 min left" at "1 min left."
3. **Huwag basahin ang script verbatim** — gamitin bilang guide. Maging natural at conversational.
4. **I-prepare ang live demo** — i-open na ang browser tabs bago magsimula. Siguruhing may test data na.
5. **Mag-practice ng transitions** — ang handoff sa pagitan ng speakers ay dapat smooth at mabilis.
6. **Para sa Q&A** — kung hindi alam ang sagot, huwag mag-imbento. Sabihin: "Magandang tanong po iyan. Sa current version, hindi pa po included iyan, pero puwedeng maging future enhancement."

---

*Document prepared for CEP-ONHS Pre-Final Defense Presentation*
*Total Presentation: 20 minutes | Q&A: 10 minutes | Grand Total: 30 minutes*
*School Year 2025–2026*
