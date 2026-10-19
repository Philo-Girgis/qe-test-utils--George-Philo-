# Pair Retrospective: test_utils library

- Pair members: Philo Girgis, George George
- Repository / branch / PR link: [repo_link](https://github.com/Philo-Girgis/qe-test-utils--George-Philo-)
- Date and total time spent: 2hrs 45mins

## 1. Role-swap log

Fill one row per 30-minute block (add rows if you swapped more often).

| Block | Minutes | Driver | Navigator | What we built | Last commit hash (short) |
|---|---|---|---|---|---|
| 1 | 0-30 | [George] | [Philo] | Completed M1 Validators | 67f6ffe |
| 2 | 30-60 | [Philo] | [George] | Added email and password validator |  9893e21
| 3 | 60-90 | [George] | [Philo] | Completed Validators.pt from test_utils | 9c224cf |
| 4 | 90-120 | [Philo] | [George] | Generators block3-4 | fa4005e |
| 5 | 120-150 | [George] | [Philo] | finished M3 | 9464908 |
| 6 | 150-180 | [Philo] | [George] | Completed M4 Timing Decorator | ecc6c0d |
| 7 | 180-210 | [George] | [Philo] | M5 Bloc completed: Lambda Functions | 926e749 |
| 8 | 210-240 | [Philo] | [George] | Completed demo report | 4f0eae4 |



## 2. What went well in how we worked together?
The navigator realized that the defaults dict todo in make_test_case meant creating a dictionary with default values instead of using default_dict.

## 3. What was difficult?
- Technically: Interpreting what the question required
- As a team (communication, pace, disagreement, git hand-offs): resisting the urge to write the code ourselves

## 4. What did each of us learn from the other?
- Philo learned from George: the solution is often less complicated than it seems
- George learned from Philo: The solution isn't always simple. 

## 5. Our code
- The function we are proudest of, and why: the decorator function is very clean
- The function that most needs improvement, and how: our validators could be simplified
- One bug we hit and how we found it (error message, what we tried, the fix): is_valid_email was breaking at the split because we had used and logic instead of or logic

## 6. Git collaboration
- Did every swap follow commit, push, pull? What went wrong when we skipped a step? Every swap followed the order and we made sure to communicate before any step
- Did we get a merge conflict? How did we resolve it (or why not)? No merge conflicts occured because we followed the order and communicated
- Output of `git shortlog -sne` (paste):
5  georggeo23 <georgechris2003@gmail.com>
4  Philo-Girgis <106279530+Philo-Girgis@users.noreply.github.com>

## 7. Next time
- Two things we would do differently: Read the question carefully before immediately jumping to code
- Self-rating, 1 (poor) to 5 (excellent): communication 4, keeping to the swap timer 4.275, understanding every line 5

## 8. Final check
Paste the last lines of `python3 check_exercise.py` (the "x/y checks passed" line): 20/20 checks passed
ALL CHECKS PASSED: library, report and files are in place. Now finish the Definition of Done.

