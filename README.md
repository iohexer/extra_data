# Supplementary data description

- 1. comments\_data\_info: Based on the number of stars, 500 projects were selected from Github to verify the number of function annotations available for analysis. Only 1.2% of these projects do not have annotations available for PAT analysis.(Each array implies a project, the first element represents the number of all functions in the project and the second element represents the number of functions that contain analyzable comments.)
- 2. wordpress\_plugins\_popular100: To prove that WordPress plugins generally use user-defined santiziers provided by WordPress, we selected 100 of the most popular WordPress plugins to test whether they used the user-defined sanitizers in WordPress core. The result is that 100% of the plugins use the user-defined sanitizer at least once.
- 3. To justify the choice of threshold for the formula is reasonable, we use the linear, square, and cubic versions of the formula respectively. Then test the number of TPs in the top of the results ranking. The following figure shows the percentage of TP numbers in the top of the results using different formulas.

![fig](https://user-images.githubusercontent.com/106004681/179501702-172e59a6-bbef-47b5-8e65-ddf554efe0e8.png)

- 4. A collection of user-defined sanitizers collected from popular real-world CMSs.
- 5. The main code of specification inference in PAT.
