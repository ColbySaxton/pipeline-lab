# pipeline-lab

**Part 1**

Green run screenshot: ![First Green Run](firstgreenrun.png)
In one sentence: what event started this run, and who started it?
The definition in the ci yml file that defined that on push to the main branch kicked off this run. So it was started by me when I commited code to main.

**Part 2**

My prediction of which test would fail: test_boundary_exactly_24_hours_is_free() — was I right? yes
Red run screenshot: ![Introduce off by one bug](introduceoffbyonebug.png)
Green-again screenshot: ![Fix off by one bug](fixoffbyonebug.png)


In one sentence: what would this bug have cost if there were no pipeline?
If there were no pipeline, this error would have cost an end user a late fee if they had cancelled at the previous boundary. This would have cost the company time and money to reimburse the end use and resolve this issue and it would have caused a high severity and high priority bug causing the development team to reallocate their time.
