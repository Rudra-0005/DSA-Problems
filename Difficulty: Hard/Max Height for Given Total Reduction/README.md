<h2><a href="https://www.geeksforgeeks.org/problems/cut-woods/1">Max Height for Given Total Reduction</a></h2><h3>Difficulty Level : Difficulty: Hard</h3><hr><div class="problems_problem_content__Xm_e[...]
<p><span style="font-size: 14pt;"><strong>Note: </strong>It is guaranteed that sum(arr) ≥ m, so a valid height h (including possibly h = 0) always exists.</span></p>
<p><span style="font-size: 18px;"><strong>Examples:</strong></span></p>
<pre><span style="font-size: 14pt;"><strong>Input:</strong> arr[] = [20, 15, 10, 17], m = 7
<strong>Output:</strong> 15<br><strong>Explanation:</strong> At h = 15, tree1 gives 20-15 = 5 metres, tree4 gives 17-15 = 2 metres, and the other two trees give 0 (they're shorter than 15). Total w[...]
</span></pre>
<pre><span style="font-size: 14pt;"><strong>Input: </strong>arr[] = [4, 42, 40, 26, 46], m = 20
<strong>Output:</strong> 36<br><strong>Explanation:</strong> At h = 36, the trees taller than 36 give 42-36 = 6, 40-36 = 4, and 46-36 = 10 metres respectively. Total wood = 6 + 4 + 10 = 20, which e[...]
<p><span style="font-size: 14pt;"><strong>Constraints:</strong><br>1 ≤ arr.size() ≤ 10<sup>6</sup><br>1 ≤ arr[i] ≤ 10<sup>6</sup><br>1 ≤ m ≤ 2×10<sup>6</sup></span></p></div>
