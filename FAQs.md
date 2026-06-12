# Frequently Asked Questions (FAQs)

Welcome! This FAQ is designed to answer common administrative, IT, and research-related questions for members of the Chemical Data Lab (CDL) at Palacký University Olomouc (UPOL).

---

## 1. General IT & Departmental Setup

### How do I access university IT systems?
* **UPOL Portal:** Go to [portal.upol.cz](https://portal.upol.cz/) and log in using your student/employee ID (Portal ID) and password. This is your gateway to STAG, email, and cards.
* **Eduroam Wi-Fi:** Set up Wi-Fi using your portal credentials (usually `username@upol.cz` or `ID@upol.cz`) by downloading the configuration utility from [wifi.upol.cz](https://wifi.upol.cz).
* **VPN Access:** To access department clusters, MolMeDB development servers, and scientific journals from home, configure the FortiClient VPN following the instructions on [portal.upol.cz (IT section)](https://portal.upol.cz).
* **Communication:** We use **MS Teams** for group chats, sharing documents, and Friday meetings. Access it with your UPOL account.

---

## 2. Onboarding by Academic Level

### 🎓 Bachelor (Bc.) & Master (Mgr.) Students
* **Where do I work?** You can work in the student study rooms at the Faculty of Science or coordinate with your supervisor for desk space in the department (room 3.009 or nearby).
* **STAG Course Enrollment:** Register your Bachelor/Diploma thesis topics and courses through STAG via the UPOL Portal. Make sure your supervisor (e.g., Karel Berka) is assigned.
* **Computing Setup:** You will primarily use your personal laptop. Install:
  * Python (Anaconda or Miniconda) with Jupyter notebooks.
  * [PyMOL](https://pymol.org/) (use the educational license or open-source build).
  * Git for version control.

### 🥼 PhD Students
* **Employment & Contracts:** Visit the HR department at the Faculty of Science deanery to sign your doctoral study agreements and any research employment contracts.
* **Office & Keys:** Coordinate with the department secretary (3rd floor) to get your office desk assignment, department keys, and building chip access.
* **Heavy Computations:** 
  * Apply for an account on the local KFC department servers.
  * Apply for a free account on the Czech national supercomputing grid **MetaCentrum** ([metacentrum.cz](https://www.metacentrum.cz/)).
* **Teaching & Duties:** PhD students are expected to assist with seminars or laboratories (e.g., Physical Chemistry labs, Cheminformatics). Confirm your teaching schedule with Karel.

### 🧪 Post-docs
* **HR & Registration:** Ensure your foreign researcher registration (if applicable) and employee profile are complete at the HR department.
* **Grant Reporting & Databases:** Coordinate with Karel regarding your specific project responsibilities (e.g., ELIXIR-CZ, Czech Science Foundation - GAČR). Ensure your publications are registered in the UPOL OBD system.
* **Cluster & Server Admin:** Request root or advanced access to local computing nodes if your project requires deploying custom databases or web services (like MolMeDB, ChannelsDB).

---

## 3. Git & Open Science

### Where do we publish our code?
We host our research code, database repositories, and documentation on GitHub:
* [github.com/KarelBerka](https://github.com/KarelBerka)
* [github.com/jiras95/MolMeDB](https://github.com/jiras95) (MolMeDB development)

### What emoji cheat sheet can I use for markdown commit messages?
We love expressive commits! Use: [https://gitmoji.dev/](https://gitmoji.dev/)
* 🧪 `:test_tube:` for adding tests
* 🐛 `:bug:` for fixing bugs
* 📝 `:memo:` for documentation
* ⚡ `:zap:` for performance improvements
