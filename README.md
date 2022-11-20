<!-- 
  <<< Author notes: Header of the course >>> 
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses Creative Commons Attribution 4.0 International.
-->

# Introducere în GitHub

_Învață să folosești GitHub, în mai puțin de o oră._

<!-- 
  <<< Author notes: Start of the course >>> 
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
  Each step should be wrapped in <details>/<summary>, with an `id` set.
  The start <details> should have `open` as well.
  Do not use quotes on the <details> tag attributes.
-->

<!--step0

People use GitHub to build some of the most advanced technologies in the world. Whether you’re visualizing data or building a new game, there’s a whole community and set of tools on GitHub that can help you do it even better. GitHub Skills’ “Introduction to GitHub” course guides you through everything you need to start contributing in less than an hour.

- **Cui se adresează?**: New developers, new GitHub users, and students.
- **Ce vei învăța**: We'll introduce repositories, branches, commits, and pull requests.
- **Ce vei realiza?**: We'll make a short Markdown file you can use as your [profile README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme).
- **Cerințe preliminare**: None. This course is a great introduction for your first day on GitHub.
- **Cât durează**: This course is four steps long and takes less than one hour to complete.

## Cum să încep acest curs?

1. Above these instructions, right-click **Use this template** and open the link in a new tab.
   ![Use this template](https://user-images.githubusercontent.com/1221423/169618716-fb17528d-f332-4fc5-a11a-eaa23562665e.png)
2. In the new tab, follow the prompts to create a new repository.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository—private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   ![Create a new repository](https://user-images.githubusercontent.com/1221423/169618722-406dc508-add4-4074-83f0-c7a7ad87f6f3.png)
3. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.

endstep0-->

<!-- 
  <<< Author notes: Step 1 >>> 
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

<details id=1 open>
<summary><h2>Pasul 1: Create a branch (Creează o ramură)</h2></summary>

_Bun venit la "Introducere în GitHub"! :wave:_

**Ce este GitHub?**: GitHub este o platformă colaborativă care folosește [Git](https://docs.github.com/get-started/quickstart/github-glossary#git) pentru versionare. GitHub este un spațiu public unde poți să împărtășești și poți să contribui la programe [open-source](https://docs.github.com/get-started/quickstart/github-glossary#open-source).
<br>:tv: [Video: What is GitHub?](https://www.youtube.com/watch?v=w3jLJU7DT5E)

**Ce este un repository?**: Un [repository](https://docs.github.com/get-started/quickstart/github-glossary#repository) este o colecție de fișiere și dosare. Un repository ține evidența versiunilor de fișiere și dosare.
<br>:tv: [Video: Exploring a repository](https://www.youtube.com/watch?v=R8OAwrcMlRw)

**Ce este un branch?**: Un [branch](https://docs.github.com/en/get-started/quickstart/github-glossary#branch) este o versiune paralelă a unui repository. În mod implicit, un repository conține un branch (ramură) cu denumirea `main`, fiind conciderat versiunea definitivă (principală). Într-un repository care îți aparține, poți crea ramuri suplimentare, pe lângă `main`. Poți folosi simultan mai multe ramuri pentru diferite versiuni ale proiectului tău.

Ramurile suplimentare sunt utile pentru a testa diverse modificări, fără a altera versiunea `main`. Ramurile îți permit să separi ceea ce este în lucru de ramura principală `main`. Cu alte cuvinte, munca fiecăruia este în siguranță în timp ce tu aduci diverse îmbunătățiri sau contribui.
<br>:tv: [Video: Branches](https://www.youtube.com/watch?v=xgQmu81G1yY)

**Ce este un profile README?**: Un fișier [profile README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme) este, de fapt, o secțiune de tip "About me" (Despre) pentru profilul tău GitHub, secțiune în care poți să împărtășești ceva despre tine cu comunitatea GitHub.com. GitHub afișează informațiile din profile README în partea de sus a paginii tale de profil.

### :keyboard: Activitate: Prima ta ramură (branch)

1. Open a new browser tab, and navigate to this same repository. Then, work on the steps in your second tab while you read the instructions in this tab.
2. Navigate to the **Code** tab.
3. Click on the **main** branch drop-down.<br>
   <img alt="image showing my-first-branch entry" src="/images/my-first-branch.png"/>
4. In the field, enter a name for your branch: `my-first-branch`.
5. Click **Create branch: my-first-branch** to create your branch.
6. Move on to Step 2!<br>
   **Note**: If you made a public repository, and want to confirm you correctly set up your first branch, wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically close this step and open the next one.

</details>

<!-- 
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=2>
<summary><h2>Pasul 2: Commit a file (Dă commit la un fișier)</h2></summary>

_Ai creat un branch (o ramură)! :tada:_

Crearea unei ramuri îți permite să editezi propriul proiect fără să modifici ramura principală `main`. Acum, pentru că ai o ramură, este timpul să creezi un fișier și să execuți prima ta acțiune de tip commit!

**Ce este un commit?**: Un [commit](https://docs.github.com/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits) reprezintă un se de actualizări asupra fișierelor și dosarelor din proiectul tău. Un commit se face într-o ramură.

### :keyboard: Activitate: Primul tău commit

The following steps will guide you through the process of committing a change on GitHub. Committing a change requires first adding a new file to your new branch. 

1. On the **Code** tab, make sure you're on your new branch `my-first-branch`.
2. Select the **Add file** drop-down and click **Create new file**.<br>
   ![create new file option](/images/create-new-file.png)
3. In the **Name your file...** field, enter `PROFILE.md`.
4. In the **Edit new file** area, copy the following content to your file:
   ```
   Welcome to my GitHub profile!
   ```
   <img alt="profile.md file screenshot" src="/images/my-profile-file.png"/>
5. For commits, you can enter a short commit message that describes what changes you made. This message helps others know what's included in your commit. GitHub offers a simple default message, but let's change it slightly for practice. First, enter `Add PROFILE.md` in the first text-entry field below **Commit new file**. Then, if you want to confirm what your screen should look like, expand the dropdown below.
   <details>
   <summary> Expand to see the screenshot.</summary>
   <img alt="screenshot of adding a new file with a commit message" src="/images/commit-full-screen.png" />
   </details>
6. In this lesson, we'll ignore the other fields and click **Commit new file**.
7. Move on to Step 3! <br>
   **Note**: Like before, you can wait about 20 seconds, then refresh this page (the one you're following instructions from) and [GitHub Actions](https://docs.github.com/en/actions) will automatically close this step and open the next one.

</details>

<!-- 
  <<< Author notes: Step 3 >>> 
  Just a historic note: the previous version of this step forced the learner
  to write a pull request description,
  checked that `main` was the receiving branch,
  and that the file was named correctly.
-->

<details id=3>
<summary><h2>Pasul 3: Open a pull request (Deschide un spațiu de colaborare)</h2></summary>

_Frumos lucrat cu acel commit :sparkles:_

Acum, pentru că ai executat un commit, este timpul să împărtășești modificările pe care le propui, printr-un pull request (spațiu de colaborare)!

**Ce este un pull request?**: Un pull request reprezintă un spațiu de colaborare. Acesta le afișează celorlalți modificările de pe o ramură a ta. În acest pull request se păstrează modificările pe care le-ai făcut pe ramura ta și sunt propuse a fi aplicate ramurii `main` (principale).
<br>:tv: [Video: Introduction to pull requests](https://youtu.be/kJr-PIfLDl4)

### :keyboard: Activitate: Creează un pull request (spațiu de colaborare)

You may have noticed after your commit that a message displayed indicating your recent push to your branch and providing a button that says **Compare & pull request**.

![screenshot of message and button](/images/compare-and-pull-request.png)

 If you want, feel free to click **Compare & pull request**, and then skip to step 6 below. If you don't click the button, the instructions below walk you through manually setting up the pull request.

1. Click on the **Pull requests** tab in your repository.
2. Click **New pull request**.
3. In the **base:** dropdown, make sure **main** is selected.
4. Select the **compare:** dropdown, and click `my-first-branch`. <br>
   <img alt="screenshot showing both branch selections" src="/images/pull-request-branches.png"/>
5. Click **Create pull request**.
6. Enter a title for your pull request: `Add my first file`.
7. The next field helps you provide a description of the changes you made. Feel free to add a description of what you’ve accomplished so far. As a reminder, you have: created a branch, created a file and made a commit! <br>
   <img alt="screenshot showing pull request" src="/images/Pull-request-description.png"/>
8. Click **Create pull request**.
9. Move on to Step 4! <br>
   **Note**: Like before, you can wait about 20 seconds, then refresh this page (the one you're following instructions from) and [GitHub Actions](https://docs.github.com/en/actions) will automatically close this step and open the next one. As a perk, you may see evidence of GitHub Actions running on the tab with the pull request opened! The image below shows a line you might see on your pull request after the Action finishes running.<br>
   <img alt="screenshot of an example of an actions line" src="/images/Actions-to-step-4.png"/>

</details>

<!-- 
  <<< Author notes: Step 4 >>> 
  Just a historic note: The previous version of this step required responding
  to a pull request review before merging. The previous version also handled
  if users accidentally closed without merging.
-->

<details id=4>
<summary><h2>Pasul 4: Merge your pull request (Actualizează ramura principală)</h2></summary>

_Bine lucrat, amice! :sunglasses:_

Ai reușit să creezi un pull request. Acum poți să faci actualizarea aplicând ceea ce ai în pull request (spațiul de colaborare).

**Ce este o operație de actualizare _merge_**: O actualizare [merge](https://docs.github.com/en/get-started/quickstart/github-glossary#merge) aplică ramurii principale `main` modificările pe care le ai în pull request și în branch (ramura corespunzătoare).
<br>:tv: [Video: Understanding the GitHub flow](https://www.youtube.com/watch?v=PBI2Rz-ZOxU)

Este posibil să fi observat la pasul anterior să se execută o acțiune care te conduce la următorul pas. Ar trebui să aștepți până se termină aceasta, înainte să poți executa un merge (actualizare) pe baza propunerilor din pull request. Va fi posibil atunci când butonul merge pull request va avea culoarea verde.

![screenshot of green merge pull request button](/images/Green-merge-pull-request.png)
### :keyboard: Activitate: Aplică modificările prin Merge pull request

1. Click **Merge pull request**.
1. Click **Confirm merge**.
1. Once your branch has been merged, you don't need it anymore. To delete this branch, click **Delete branch**.<br>
   <img alt="screenshot showing delete branch button" src="/images/delete-branch.png"/>
2. Check out the **Finish** step to see what you can learn next!<br>
   **Note**: Like before, you can wait about 20 seconds, then refresh this page (the one you're following instructions from) and [GitHub Actions](https://docs.github.com/en/actions) will automatically close this step and open the next one.

</details>

<!-- 
  <<< Author notes: Finish >>> 
  Review what we learned, ask for feedback, provide next steps.
-->

<details id=X>
<summary><h2>Finalizează</h2></summary>

_Felicitări, ai finalizat acest curs și ai intrat în lumea dezvoltatorilor!_

<img src=https://octodex.github.com/images/collabocats.jpg alt=celebrate width=300 align=right>

Hai să recapitulăm reușitele tale:

- Ai învățat despre GitHub, repositorii, branch-uri (ramuri), commit (salvare) și pull request (spațiu de colaborare).
- Ai creat un branch, un făcut un commit și un pull request.
- Ai actualizat printr-un merge pentru pull request.
- Ți-ai adus prima contribuție! :tada:

### Ce urmează?

  If you'd like to make a profile README, use the simplified instructions below or follow the instructions in the [Managing your profile README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme) article.
  1. Make a new public repository with a name that matches your GitHub username.
  2. Create a file named `README.md` in its root. The "root" means not inside any folder in your repository.
  3. Edit the contents of the `README.md` file.
  4. If you created a new branch for your file, open and merge a pull request on your branch.
  5. We'd love to see your new profile! Share your profile on social media and tag us!
  6. Lastly, we'd love to hear what you thought of this course [in our discussion board](https://github.com/skills/.github/discussions).

Verifică aceste resurse pentru a învăța mai multe sau pentru a te implica:
- Ești elev sau student? Încearcă acest [Student Developer Pack](https://education.github.com/pack).
- [Take another GitHub Skills course](https://github.com/skills).
- [Read the GitHub Getting Started docs](https://docs.github.com/en/get-started).
- Pentru a găsi proiecte la care să contribui, mergi la [GitHub Explore](https://github.com/explore).

</details>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Primești ajutor (în limba engleză): [Post in our discussion board](https://github.com/skills/.github/discussions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2022 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [CC-BY-4.0 License](https://creativecommons.org/licenses/by/4.0/legalcode)
