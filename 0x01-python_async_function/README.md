# Python - Async
<table data-sourcepos="9:1-19:79">
<thead>
<tr data-sourcepos="9:1-9:22">
<th align="center" data-sourcepos="9:2-9:7">Task</th>
<th align="center" data-sourcepos="9:9-9:21">Description</th>
</tr>
</thead>
<tbody>
<tr data-sourcepos="11:1-11:74">
<td align="center" data-sourcepos="11:2-11:19">0-basic_async_syntax.py</td>
<td align="center" data-sourcepos="11:21-11:73">Write an asynchronous coroutine that takes in an integer argument (max_delay, with a default value of 10) named wait_random that waits for a random delay between 0 and max_delay (included and float value) seconds and eventually returns it.</td>
</tr>
<tr data-sourcepos="12:1-12:86">
<td align="center" data-sourcepos="12:2-12:27">1-concurrent_coroutines.py</td>
<td align="center" data-sourcepos="12:29-12:85">aImport wait_random from the previous python file that you’ve written and write an async routine called wait_n that takes in 2 int arguments (in this order): n and max_delay. You will spawn wait_random n times with the specified max_delay.</td>
</tr>
<tr data-sourcepos="13:1-13:78">
<td align="center" data-sourcepos="13:2-13:11">2-measure_runtime.py</td>
<td align="center" data-sourcepos="13:13-13:77"> Measure the runtime
</td>
</tr>
<tr data-sourcepos="14:1-14:76">
<td align="center" data-sourcepos="14:2-14:8">3-tasks.py</td>
<td align="center" data-sourcepos="14:10-14:75">Function (do not create an async function, use the regular function syntax to do this) task_wait_random that takes an integer max_delay and returns a asyncio.Task</td>
</tr>
<tr data-sourcepos="15:1-15:107">
<td align="center" data-sourcepos="15:2-15:10">4-tasks.py</td>
<td align="center" data-sourcepos="15:12-15:106">Take the code from wait_n and alter it into a new function task_wait_n. The code is nearly identical to wait_n except task_wait_random is being called.</td>
</tr>
</tbody>
</table>