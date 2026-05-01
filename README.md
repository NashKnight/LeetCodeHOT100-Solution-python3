# LeetCode HOT100 Python3 题解

个人整理的 LeetCode HOT100 Python3 参考题解，共 17 个专题。

## 关于本题解

- **slides**：所有题目的思路和代码都在 slides 目录下，按专题汇总，同一题目可能有多种解法，本题解只收录了个人觉得对算法理解和实际面试有意义的解法。
- **语言**：全部使用 Python3 提交，非 Python，两者在部分写法上有差异（如 `Counter()` 等）。
- **来源**：参考官方题解、评论区各位大佬，尤其部分题目参考了 [灵茶山艾府（灵神）](https://leetcode.cn/u/endlesscheng/) 的思路。
- **代码**：在保持可读性的前提下尽量简洁，避免冗余。代码含有一些个人风格和习惯（当然也是为了可读性）把所有需要调用的自定义类或函数写成内部类/内部函数。
- **思路**：尽量追求简洁通俗，默认读者具备数据结构与算法基础。
- 思路或代码如有任何问题，欢迎指出。

---

## 题目列表

### 01 · Hashing / 哈希 · [slides](slides/01-Hashing-Q1-3.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 1 | Easy | [1](https://leetcode.cn/problems/two-sum/) | 两数之和 |
| 2 | Medium | [49](https://leetcode.cn/problems/group-anagrams/) | 字母异位词分组 |
| 3 | Medium | [128](https://leetcode.cn/problems/longest-consecutive-sequence/) | 最长连续序列 |

### 02 · Two Pointers / 双指针 · [slides](slides/02-TwoPointers-Q4-7.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 4 | Easy | [283](https://leetcode.cn/problems/move-zeroes/) | 移动零 |
| 5 | Medium | [11](https://leetcode.cn/problems/container-with-most-water/) | 盛最多水的容器 |
| 6 | Medium | [15](https://leetcode.cn/problems/3sum/) | 三数之和 |
| 7 | Hard | [42](https://leetcode.cn/problems/trapping-rain-water/) | 接雨水 |

### 03 · Sliding Window / 滑动窗口 · [slides](slides/03-SlidingWindow-Q8-9.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 8 | Medium | [3](https://leetcode.cn/problems/longest-substring-without-repeating-characters/) | 无重复字符的最长子串 |
| 9 | Medium | [438](https://leetcode.cn/problems/find-all-anagrams-in-a-string/) | 找到字符串中所有字母异位词 |

### 04 · Substring / 子串 · [slides](slides/04-Substring-Q10-12.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 10 | Medium | [560](https://leetcode.cn/problems/subarray-sum-equals-k/) | 和为 K 的子数组 |
| 11 | Hard | [239](https://leetcode.cn/problems/sliding-window-maximum/) | 滑动窗口最大值 |
| 12 | Hard | [76](https://leetcode.cn/problems/minimum-window-substring/) | 最小覆盖子串 |

### 05 · Arrays / 普通数组 · [slides](slides/05-Arrays-Q13-17.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 13 | Medium | [53](https://leetcode.cn/problems/maximum-subarray/) | 最大子数组和 |
| 14 | Medium | [56](https://leetcode.cn/problems/merge-intervals/) | 合并区间 |
| 15 | Medium | [189](https://leetcode.cn/problems/rotate-array/) | 轮转数组 |
| 16 | Medium | [238](https://leetcode.cn/problems/product-of-array-except-self/) | 除自身以外数组的乘积 |
| 17 | Hard | [41](https://leetcode.cn/problems/first-missing-positive/) | 缺失的第一个正数 |

### 06 · Matrix / 矩阵 · [slides](slides/06-Matrix-Q18-21.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 18 | Medium | [73](https://leetcode.cn/problems/set-matrix-zeroes/) | 矩阵置零 |
| 19 | Medium | [54](https://leetcode.cn/problems/spiral-matrix/) | 螺旋矩阵 |
| 20 | Medium | [48](https://leetcode.cn/problems/rotate-image/) | 旋转图像 |
| 21 | Medium | [240](https://leetcode.cn/problems/search-a-2d-matrix-ii/) | 搜索二维矩阵 II |

### 07 · Linked Lists / 链表 · [slides](slides/07-LinkedLists-Q22-35.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 22 | Easy | [160](https://leetcode.cn/problems/intersection-of-two-linked-lists/) | 相交链表 |
| 23 | Easy | [206](https://leetcode.cn/problems/reverse-linked-list/) | 反转链表 |
| 24 | Easy | [234](https://leetcode.cn/problems/palindrome-linked-list/) | 回文链表 |
| 25 | Easy | [141](https://leetcode.cn/problems/linked-list-cycle/) | 环形链表 |
| 26 | Medium | [142](https://leetcode.cn/problems/linked-list-cycle-ii/) | 环形链表 II |
| 27 | Easy | [21](https://leetcode.cn/problems/merge-two-sorted-lists/) | 合并两个有序链表 |
| 28 | Medium | [2](https://leetcode.cn/problems/add-two-numbers/) | 两数相加 |
| 29 | Medium | [19](https://leetcode.cn/problems/remove-nth-node-from-end-of-list/) | 删除链表的倒数第 N 个节点 |
| 30 | Medium | [24](https://leetcode.cn/problems/swap-nodes-in-pairs/) | 两两交换链表的节点 |
| 31 | Hard | [25](https://leetcode.cn/problems/reverse-nodes-in-k-group/) | K 个一组翻转链表 |
| 32 | Medium | [138](https://leetcode.cn/problems/copy-list-with-random-pointer/) | 随机链表的复制 |
| 33 | Medium | [148](https://leetcode.cn/problems/sort-list/) | 排序链表 |
| 34 | Hard | [23](https://leetcode.cn/problems/merge-k-sorted-lists/) | 合并 K 个升序链表 |
| 35 | Medium | [146](https://leetcode.cn/problems/lru-cache/) | LRU 缓存 |

### 08 · Binary Tree / 二叉树 · [slides](slides/08-BinaryTree-Q36-50.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 36 | Easy | [94](https://leetcode.cn/problems/binary-tree-inorder-traversal/) | 二叉树的中序遍历 |
| 37 | Easy | [104](https://leetcode.cn/problems/maximum-depth-of-binary-tree/) | 二叉树的最大深度 |
| 38 | Easy | [226](https://leetcode.cn/problems/invert-binary-tree/) | 翻转二叉树 |
| 39 | Easy | [101](https://leetcode.cn/problems/symmetric-tree/) | 对称二叉树 |
| 40 | Easy | [543](https://leetcode.cn/problems/diameter-of-binary-tree/) | 二叉树的直径 |
| 41 | Medium | [102](https://leetcode.cn/problems/binary-tree-level-order-traversal/) | 二叉树的层序遍历 |
| 42 | Easy | [108](https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/) | 将有序数组转换为二叉搜索树 |
| 43 | Medium | [98](https://leetcode.cn/problems/validate-binary-search-tree/) | 验证二叉搜索树 |
| 44 | Medium | [230](https://leetcode.cn/problems/kth-smallest-element-in-a-bst/) | 二叉搜索树中第 K 小的元素 |
| 45 | Medium | [199](https://leetcode.cn/problems/binary-tree-right-side-view/) | 二叉树的右视图 |
| 46 | Medium | [114](https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/) | 二叉树展开为链表 |
| 47 | Medium | [105](https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | 从前序与中序遍历序列构造二叉树 |
| 48 | Medium | [437](https://leetcode.cn/problems/path-sum-iii/) | 路径总和 III |
| 49 | Medium | [236](https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/) | 二叉树的最近公共祖先 |
| 50 | Hard | [124](https://leetcode.cn/problems/binary-tree-maximum-path-sum/) | 二叉树中的最大路径和 |

### 09 · Graph / 图论 · [slides](slides/09-Graph-Q51-54.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 51 | Medium | [200](https://leetcode.cn/problems/number-of-islands/) | 岛屿数量 |
| 52 | Medium | [994](https://leetcode.cn/problems/rotting-oranges/) | 腐烂的橘子 |
| 53 | Medium | [207](https://leetcode.cn/problems/course-schedule/) | 课程表 |
| 54 | Medium | [208](https://leetcode.cn/problems/implement-trie-prefix-tree/) | 实现 Trie (前缀树) |

### 10 · Backtracking / 回溯法 · [slides](slides/10-Backtracking-Q55-62.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 55 | Medium | [46](https://leetcode.cn/problems/permutations/) | 全排列 |
| 56 | Medium | [78](https://leetcode.cn/problems/subsets/) | 子集 |
| 57 | Medium | [17](https://leetcode.cn/problems/letter-combinations-of-a-phone-number/) | 电话号码的字母组合 |
| 58 | Medium | [39](https://leetcode.cn/problems/combination-sum/) | 组合总和 |
| 59 | Medium | [22](https://leetcode.cn/problems/generate-parentheses/) | 括号生成 |
| 60 | Medium | [79](https://leetcode.cn/problems/word-search/) | 单词搜索 |
| 61 | Medium | [131](https://leetcode.cn/problems/palindrome-partitioning/) | 分割回文串 |
| 62 | Hard | [51](https://leetcode.cn/problems/n-queens/) | N 皇后 |

### 11 · Binary Search / 二分查找 · [slides](slides/11-BinarySearch-Q63-68.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 63 | Easy | [35](https://leetcode.cn/problems/search-insert-position/) | 搜索插入位置 |
| 64 | Medium | [74](https://leetcode.cn/problems/search-a-2d-matrix/) | 搜索二维矩阵 |
| 65 | Medium | [34](https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/) | 在排序数组中查找元素的第一个和最后一个位置 |
| 66 | Medium | [33](https://leetcode.cn/problems/search-in-rotated-sorted-array/) | 搜索旋转排序数组 |
| 67 | Medium | [153](https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/) | 寻找旋转排序数组中的最小值 |
| 68 | Hard | [4](https://leetcode.cn/problems/median-of-two-sorted-arrays/) | 寻找两个正序数组的中位数 |

### 12 · Stack / 栈 · [slides](slides/12-Stack-Q69-73.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 69 | Easy | [20](https://leetcode.cn/problems/valid-parentheses/) | 有效的括号 |
| 70 | Medium | [155](https://leetcode.cn/problems/min-stack/) | 最小栈 |
| 71 | Medium | [394](https://leetcode.cn/problems/decode-string/) | 字符串解码 |
| 72 | Medium | [739](https://leetcode.cn/problems/daily-temperatures/) | 每日温度 |
| 73 | Hard | [84](https://leetcode.cn/problems/largest-rectangle-in-histogram/) | 柱状图中最大的矩形 |

### 13 · Heap / 堆 · [slides](slides/13-Heap-Q74-76.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 74 | Medium | [215](https://leetcode.cn/problems/kth-largest-element-in-an-array/) | 数组中的第 K 个最大元素 |
| 75 | Medium | [347](https://leetcode.cn/problems/top-k-frequent-elements/) | 前 K 个高频元素 |
| 76 | Hard | [295](https://leetcode.cn/problems/find-median-from-data-stream/) | 数据流的中位数 |

### 14 · Greedy / 贪心算法 · [slides](slides/14-Greedy-Q77-80.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 77 | Easy | [121](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/) | 买卖股票的最佳时机 |
| 78 | Medium | [55](https://leetcode.cn/problems/jump-game/) | 跳跃游戏 |
| 79 | Medium | [45](https://leetcode.cn/problems/jump-game-ii/) | 跳跃游戏 II |
| 80 | Medium | [763](https://leetcode.cn/problems/partition-labels/) | 划分字母区间 |

### 15 · Dynamic Programming / 动态规划 · [slides](slides/15-DynamicProgramming-Q81-90.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 81 | Easy | [70](https://leetcode.cn/problems/climbing-stairs/) | 爬楼梯 |
| 82 | Easy | [118](https://leetcode.cn/problems/pascals-triangle/) | 杨辉三角 |
| 83 | Medium | [198](https://leetcode.cn/problems/house-robber/) | 打家劫舍 |
| 84 | Medium | [279](https://leetcode.cn/problems/perfect-squares/) | 完全平方数 |
| 85 | Medium | [322](https://leetcode.cn/problems/coin-change/) | 零钱兑换 |
| 86 | Medium | [139](https://leetcode.cn/problems/word-break/) | 单词拆分 |
| 87 | Medium | [300](https://leetcode.cn/problems/longest-increasing-subsequence/) | 最长递增子序列 |
| 88 | Medium | [152](https://leetcode.cn/problems/maximum-product-subarray/) | 乘积最大子数组 |
| 89 | Medium | [416](https://leetcode.cn/problems/partition-equal-subset-sum/) | 分割等和子集 |
| 90 | Hard | [32](https://leetcode.cn/problems/longest-valid-parentheses/) | 最长有效括号 |

### 16 · Multidimensional DP / 多维动态规划 · [slides](slides/16-MultidimensionalDynamicProgramming-Q91-95.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 91 | Medium | [62](https://leetcode.cn/problems/unique-paths/) | 不同路径 |
| 92 | Medium | [64](https://leetcode.cn/problems/minimum-path-sum/) | 最小路径和 |
| 93 | Medium | [5](https://leetcode.cn/problems/longest-palindromic-substring/) | 最长回文子串 |
| 94 | Medium | [1143](https://leetcode.cn/problems/longest-common-subsequence/) | 最长公共子序列 |
| 95 | Medium | [72](https://leetcode.cn/problems/edit-distance/) | 编辑距离 |

### 17 · Tricks / 技巧 · [slides](slides/17-Tricks-Q96-100.pdf)

| # | Difficulty | 题号 | 题目 |
|---|-----------|------|------|
| 96 | Easy | [136](https://leetcode.cn/problems/single-number/) | 只出现一次的数字 |
| 97 | Easy | [169](https://leetcode.cn/problems/majority-element/) | 多数元素 |
| 98 | Medium | [75](https://leetcode.cn/problems/sort-colors/) | 颜色分类 |
| 99 | Medium | [31](https://leetcode.cn/problems/next-permutation/) | 下一个排列 |
| 100 | Medium | [287](https://leetcode.cn/problems/find-the-duplicate-number/) | 寻找重复数 |
