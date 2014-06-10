# Instructions

* **Choose a Story:**
  * New developers start with [Small Tech Tasks](https://github.com/rapidftr/tracker/issues?labels=Estimate%3A+Small%2CStatus%3A+2.+Ready%2CType%3A+Tech+Task&milestone=6&page=1&state=open)
  * New QAs start with [Small Dev Complete Tasks](https://github.com/rapidftr/tracker/issues?labels=Estimate%3A+Small%2CType%3A+Tech+Task%2CStatus%3A+4.+Dev+Complete&milestone=6&page=1&state=open)
  * At minimum, filter by [*Free to Play* label and *Status: Ready* label](https://github.com/rapidftr/tracker/issues?labels=Status%3A+4.+Dev+Complete&milestone=6&page=1&state=open)
  * Or check the [Waffle](https://waffle.io/rapidftr/tracker) board. Same story list in a Kanban board
* **Implement:**
  * **Post a comment** saying you're going to work on this story, so that nobody else picks it up. Otherwise stories will get mixed up, especially in code jams!
  *
  * Do your wizardry
  * Raise a pull request whenever you have something ready
  * We'll mark the story as **In Dev** (or In QA for automation stories) when you raise the pull request
  * In the pull request, mention the story number. Just add the word "rapidftr/tracker#<story-no>" somewhere, e.g. "this implements rapidftr/tracker#34". This will link your pull request to the appropriate story
* **Validate:**
  * Check the Build Status. We use Travis-CI, so once you raise a pull request, you'll find (in a short while) notices in the pull request saying "Travis Build is running". Click on it to find the test case results, and make sure your code passes all tests
  * Look for code review comments in the pull request
  * Add Automation Tests for your story. We use Cucumber so it is not difficult to write some of your own scenarios. Being an open source project, the only way to maintain code correctness is through tests
* **Merge:**
  * Thank you so much for getting things done. We'll merge your pull request
