# 🧩Arrays & Hashing

## 📦Prerequisites ✅

- **Big‑O basics:** array index access `O(1)`, search in array `O(n)`, `dict/set` average lookup/insert `O(1)`.
- **Arrays (Python `list`):** indexing, iteration (`for`, `enumerate`), two pointers, sliding window, prefix/suffix basics.
- **Hashing (`dict` / `set`):**
  - `set` for **existence** checks (duplicates, seen elements).
  - `dict` for **mapping/counting** (value→index, frequency).
  - Know `d.get(key, default)` (common for counting).
- **Common patterns:** frequency counting (anagram), seen set/map (two-sum), grouping by key (group anagrams).
- **Tip:** if keys are limited (like lowercase `a-z`), a fixed array of size `26` can replace a hash map.

## Basic Arrays & Stack

- **Static Array — fixed size, contiguous memory:**

<iframe
  src="../dump/arrays_static_dynamic_stack.html"
  width="100%"
  height="650"
  style="border:1px solid #ccc; border-radius:8px;"
  title="Static/Dynamic Array and Stack interactive view"
></iframe>

If the inline preview does not render in your markdown viewer, open it directly: [Open interactive notes page](../dump/arrays_static_dynamic_stack.html).
