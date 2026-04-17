# Program evaluation project repositories

This contains links to all the standalone repositories I use for the second generation of [problem sets for my program evaluation class](https://evalsp26.classes.andrewheiss.com/assignment/), starting in Spring 2026.

Each is in its own repository so it's easier to (1) make copies in the future and (2) deploy these projects to Posit.cloud without needing to upload a bunch of individual files or move them around after uploading a .zip there


## Semester-specific customization

### Process for distributing these to students

- Make a copy of the repository somehow (git clone, download a zip file, clone it through Posit.cloud's "New Project" dialog, whatever)
- Delete `answers.qmd` and `build_data.R`
- Change `SEMESTER YEAR` in the subtitle YAML setting in `your-name_problem-set-x.qmd` to something more accurate (e.g. "Spring 2026" or whatever)
- Make sure any links that include "sp26" are updated

### Process for making the answer key

- Make a copy of the repository somehow (git clone, download a zip file, whatever)
- Change `SEMESTER YEAR` in the subtitle YAML setting in `answers.qmd` to something more accurate (e.g. "Spring 2026" or whatever)
- Change the author and date too
- Make sure any links that include "sp26" are updated
- Run `quarto::quarto_render()` inside `build_data.R`


## Project repositories

### Problem sets

- <https://github.com/andrewheiss/eval-projects_01-introduction>
- <https://github.com/andrewheiss/eval-projects_02-regression>
- <https://github.com/andrewheiss/eval-projects_03-rcts-ipw>
- <https://github.com/andrewheiss/eval-projects_04-diff-diff-1>
- <https://github.com/andrewheiss/eval-projects_05-diff-diff-2>
- <https://github.com/andrewheiss/eval-projects_06-rdd>
- <https://github.com/andrewheiss/eval-projects_07-iv>
- <https://github.com/andrewheiss/eval-projects_08-all-together>
- <https://github.com/andrewheiss/eval-projects_09-synthetic-data>

### Evaluation assignments

- <https://github.com/andrewheiss/eval-projects_eval-01-background>
- <https://github.com/andrewheiss/eval-projects_eval-02-measurement>
- <https://github.com/andrewheiss/eval-projects_eval-03-causal-model>
- <https://github.com/andrewheiss/eval-projects_eval-04-threats-validity>

### Exams

- <https://github.com/andrewheiss/eval-projects_01-exam> (private)
- <https://github.com/andrewheiss/eval-projects_02-exam> (private)

### Final project

- <https://github.com/andrewheiss/eval-projects_final-project>


## License

Everything is licensed under [Creative Commons Attribution (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/).
