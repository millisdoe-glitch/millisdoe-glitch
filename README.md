<div align="center">

# Hey, I'm millisdoe-glitch 👋

**Python Performance & Open-Source Contributor ⚡ | SwiftUI & Audio DSP**

[![GitHub](https://img.shields.io/badge/GitHub-millisdoe--glitch-181717?style=for-the-badge&logo=github)](https://github.com/millisdoe-glitch)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Swift](https://img.shields.io/badge/Swift-SwiftUI-F05138?style=for-the-badge&logo=swift&logoColor=white)](https://developer.apple.com/swift/)

</div>

---

### 🔧 What I Focus On

- **Performance Engineering in Python**: profiling hot paths (`cProfile`, `tracemalloc`), reducing allocations, eliminating algorithmic bottlenecks, and shipping zero-dependency speedups without breaking public APIs.
- **Testing & Verification**: every optimization is backed by reproducible benchmarks and full test suite verification.

---

### ⚡ Open-Source Performance Contributions

| Repository | Pull Request | Focus & Impact |
|:---|:---|:---|
| **networkx/networkx** | [PR #9049](https://github.com/networkx/networkx/pull/9049) | Dijkstra predecessor tracking & bidirectional BFS (`-24.4%` peak memory) |
| **mahmoud/boltons** | [PR #836](https://github.com/mahmoud/boltons/pull/836) | Fast paths for `unique`, `unique_iter`, `same`, `lstrip_iter`, and `subdict` |
| **python-attrs/attrs** | [PR #1667](https://github.com/python-attrs/attrs/pull/1667) | Optimized `asdict`, `astuple` (`1.96x`), and `fields` (`1.39x`) fast paths |
| **more-itertools/more-itertools** | [PR #1370](https://github.com/more-itertools/more-itertools/pull/1370) | In-place suffix reversal in `distinct_permutations` (`+23.3%` faster) |
| **grantjenks/python-sortedcontainers** | [PR #269](https://github.com/grantjenks/python-sortedcontainers/pull/269) | Direct `copy()` for `SortedList`/`SortedKeyList`/`SortedDict` (up to `20x`) & 2-sublist indexing |
| **tartley/colorama** | [PR #450](https://github.com/tartley/colorama/pull/450) | Fast-path plain text (`8.85x`) and OSC checks in `AnsiToWin32` |
| **life4/textdistance** | [PR #122](https://github.com/life4/textdistance/pull/122) | Rolling-row DP buffers for Levenshtein & Damerau-Levenshtein (`7.5x` faster, `767x` less memory) |
| **niklasf/python-chess** | [PR #1228](https://github.com/niklasf/python-chess/pull/1228) | `__slots__` on `Piece`, `Move`, `_BoardState` & streamlined `_remove_piece_at` |
| **astanin/python-tabulate** | [PR #518](https://github.com/astanin/python-tabulate/pull/518) | Fast cell type inference, ANSI stripping, and multiline checks |
| **brean/python-pathfinding** | [PR #94](https://github.com/brean/python-pathfinding/pull/94) | Open-list heap, neighbor traversal, and loop optimizations |

---

### 🛠️ Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/SwiftUI-007AFF?style=flat-square&logo=swift&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" />
</p>
