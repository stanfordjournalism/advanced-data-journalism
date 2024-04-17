# Daily Lessons

Outline of the topics/resources for each day of class.

> Note, assignments will generally be posted in Canvas. Occassionally we'll use GitHub Classroom for code-related work.

## Week 1

### Day 1 - Course Intro and Demystifying Dot Notation

- [Course Intro Presentation][]
  - Defining "advanced"
- [Demystifying Dot Notation][]
  - High-level discussion on dot notation and Python classes and OOP. This will be the last installment in Python basics, and builds on the foundation laid during fall and winter quarters in the core [PADJ courses][]. You should complete the *Demystifying* tutorial in advance of Day 2, when there will be an in-class quiz on the material covered.
  - Complete the [Elections OOP assignment][] by Friday. *This assignment is on GitHub Classroom. See Canvas for detailed instructions.*
- Housekeeping (course resources, format, [AI policy][], etc.)

[Course Intro Presentation]: https://slides.com/serdartumgoren/advanced-data-journalism-e2186d?token=zRKg5RFQ
[Demystifying Dot Notation]: https://stanfordjournalism.github.io/data-journalism-notebooks/lab?path=classes_and_oop%2FREADME.ipynb
[Elections OOP assignment]: https://github.com/stanfordjournalism/advanced-data-journalism-assignments
[PADJ courses]: https://github.com/stanfordjournalism/padj-code
[AI policy]: https://docs.google.com/document/d/1uo8TpunjQPHB7vV9x4Wl-DxIPwf52fND_6KSaC64DxI/edit?usp=sharing


### Day 2 - OOP Wrap-up; In-class Quiz; Intro to APIs

- Discussion/Q&A on [Demystifying Dot Notation][] and related [Elections OOP Coding Challenge][] (*see Canvas assignment for details*)
- Quiz on *Demystifying* tutorial (Canvas)
- [Intro to APIs presentation][]
- Assignments reminder:
  - Elections OOP (due Friday)
  - Weekly reflection (due Sunday)
  - Senate Compromisers (due Monday).
- Hands-on work for remainder of class (student choice):
  - Start Quakebot exercise/Senate Compromisers assignment
  - Work on [Elections OOP Coding Challenge][]

[Intro to APIs presentation]: https://tinyurl.com/apis-and-the-news
[Elections OOP Coding Challenge]: https://stanfordjournalism.github.io/data-journalism-notebooks/lab/index.html?path=classes_and_oop%2Felections_oop_code_challenge.ipynb


## Week 2

### Day 3 - Web Scraping

Please clone the [Stanford Data Journalism Notebooks repo](https://github.com/stanfordjournalism/data-journalism-notebooks).


You can [use VS Code to clone](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git#_open-a-git-repository) or the command line.

```bash
git clone git@github.com:stanfordjournalism/data-journalism-notebooks.git
```

Once the repo is opened locally in VS Code, navigate to `content/web_scraping/README.ipynb` and work through all notebooks, in order. **There will be a quiz on the material next class.**

> NOTE: If you're new to browser developer tools, level up using materials for Chrome or Firefox (just pick one) in `content/web_scraping/resources.ipynb`).

### Day 4 - Quiz and CLEAN Scrapers

- Guest lecture: [Katey Rusch](https://journalism.berkeley.edu/person/katey-rusch/), from the UC Berkeley Investigative Reporting Program, on the Community Law Enforcement Accountability Network (CLEAN)
- Overview of `clean-scraper` code architecture and motivations
  - If you're still shaky on classes and functions, please review Data Journalism Notebook lessons on [classes and OOP](https://stanfordjournalism.github.io/data-journalism-notebooks/lab/index.html?path=classes_and_oop%2FREADME.ipynb)
- Begin working on [clean-scraper](https://github.com/biglocalnews/clean-scraper) - Open source scraper contributions as weekend assignment
  - [Dissect the website][] and craft a scraping strategy. Add your proposed strategy to the GitHub issue for the site
  - **Once your scraping strategy is approved**, begin implementing the code on a fork of the `clean-scraper` repo, per the [Contributor Guidelines][]
- Homework:

## Week 3

### Day 5 - CLEAN Scraping

Guided tour of the [clean-scraper][] code repository, including:

- Code architecture:
  ```
  cli -> runner -> San Diego PD scraper -> cache.download
  ```
- Code conventions: 
  - `scrape_meta` stores file artifacts in cache and produces a JSON metadata file
  - `scrape` reads JSON metadata and downloads files (to cache)
- *Scraping at scale, with a paper trail.* - aka why the complexity?
- Contributor Guidelines
  - Claim an agency by filing a GitHub Issue
  - Dissect your website and add proposed scraping plan to GH Issue
- Start writing your scraper

[clean-scraper]: https://github.com/biglocalnews/clean-scraper
[Dissect the website]: https://stanfordjournalism.github.io/data-journalism-notebooks/lab/index.html?path=web_scraping%2Fdissecting_websites.ipynb
[Contributor Guidelines]: https://github.com/biglocalnews/clean-scraper/blob/main/docs/contributing.md

## Day 6 - CLEAN Scraping continued

- Finalize scraping plans (make sure to file an Issue for your scraper on GitHub)
- Work on scrapers
