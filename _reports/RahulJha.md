---
categories:
  - GSoC
  - 2017
  - StatusReport
date: 2017-08-28
student: Rahul Jha
organisation: coala
organisation_link : https://coala.io
project: Removing dead code with Vulture
project_link: https://summerofcode.withgoogle.com/projects/#6564412442804224
tarball: https://github.com/RJ722/vulture/files/1255118/GSoC_RJ722_Rahul_Jha.tar.gz
mentors: >
 [Jendrik Seipp](https://github.com/jendrikseipp)
phase:
 - Bonding : https://gitlab.com/coala/GSoC/GSoC-2017/milestones/40
 - Phase 1 : https://gitlab.com/coala/GSoC/GSoC-2017/milestones/33
 - Phase 2 : https://gitlab.com/coala/GSoC/GSoC-2017/milestones/34
 - Phase 3 : https://gitlab.com/coala/GSoC/GSoC-2017/milestones/35
bio: >
 I'm a sophomore year student studying Electronics Engineering at Zakir Hussain
 College of Engineering and Technology, Aligarh Muslim University. For GSoC,
 I worked on [coala](https://coala.io), [vulture](https://github.com/jendrikseipp/vulture)
 and [VultureBear](https://github.com/coala/coala-bears/blob/master/bears/python/VultureBear.py).
 The main task of this project was to let VultureBear remove dead code automatically.
social:
 - GitHub:
   - username: RJ722
   - link: https://github.com/RJ722
 - GitLab:
   - username: RJ722
   - link: https://gitlab.com/RJ722
 - Gitter:
   - username: RJ722
   - link: https://gitter.im/RJ722
email: rahul722j@gmail.com
blog: https://rj722.github.io/blog
activity:
 - 0:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/2df70c12f5e4c9677098bc42f78eec2c4c839f02
   - details: >
      Add --version flag for vulture.
 - 1:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/e5012c424fdba1a6aa0b5da8e9befdf2e98e0fc9
   - details: > 
       Add tests for version.
 - 2:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/ccb0f0468849c27c14adf25a81a23f63161b0ed4
   - details: Add appveyor CI.
 - 3:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/7e41b08cbc7ef3a4076ee84c749a9a8058ed6e0c
   - details: Ship vulture as a package.
 - 4:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/f2c0cf5eb9347e6a983362e80eb029ceb31901d3
   - details: Use stdlib.py as a default whitelist.
 - 5:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/b6d492cbcc647671950a0aca38dd88345dbc3aef
   - details: Allow vulture to be executed as `python -m vulture`.
 - 6:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/db86938a37313d47efef2a672d4b9c244a268200
   - details: Choose whitelists based on imports.
 - 7:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/0dd0b309ac4986939232ab15e01615e9552a70ec
   - details: Differentiate between functions and classes.
 - 8:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/9265e582b996e9958028369bc31ad534e6ee1432
   - details: Add utils.py module.
 - 9:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/f28ddd1ba69cb1f48b0d2c0babb4211e61236438
   - details: Add count_lines function.
 - 10:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/99ca09ff44cc5b75a6911bdae3416933e8d83c35
   - details: Let item inherit from object.
 - 11:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/a081ec66419457708405f6a58b36562cc419dcaf
   - details: Add whitelist for unittest module.
 - 12:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/32df7c37fdcaff6143cfa0c4e601561daa04e9ef
   - details: Adapt ignore functions for unittest module.
 - 13:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/bdc2c481ed933214d26b746d228759c1b429bf7a
   - details: ".travis.yml: Change pypy2-5.8.0 to pypy2.7-5.8.0"
 - 14:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/3ea94d9de2ea469184cbae6e08a1b3f98c2802e9
   - details: Distribute and test vulture as a wheel file.
 - 15:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/e308e31e929fef98b3cd317839b26b9b88d49fbb
   - details: Detect unreachable code after `return` statements.
 - 16:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/982195008fbd55b08552789f2de76bfb43860af4
   - details: Detect unreachable code after `break`, `continue` and `raise`.
 - 17:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/bcb79135fed8dfaeede616577c82b0bf87ec2684
   - details: Add --min-confidence flag.
 - 18:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/947bdb855eb596800ed05a38f24c65c2f96ec343
   - details: Detect unsatisfiable while conditions.
 - 19:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/406fd8067a23549cdb3b9cd7344b7ab8e0e47b47
   - details: Detect unsatisfiable 'if' conditions.
 - 20:
   - repo: vulture
   - link: https://github.com/jendrikseipp/vulture/commit/a78a2dc14190c076bc5b9ea4cc960122480e0bd0
   - details: Detect async function definitions.
 - 21:
   - repo: coala-bears
   - link: https://github.com/coala/coala-bears/commit/52f534e0fcedabf561c0a35dbd27a195d031ff30
   - details: "VultureBear: Add SEE_MORE attribute"
 - 22:
   - repo: coala-bears
   - link: https://github.com/coala/coala-bears/commit/7f3fe6fda39332a380762c36ba800516f14a0694
   - details: >
        VultureBear: Use the Vulture API instead of the Vulture script.
 - 23:
   - repo: coala-bears
   - link: https://github.com/coala/coala-bears/commit/7ae4795cf4dbffd4af4ff4c0349063a0639e27e8
   - details: "VultureBear: Report confidence values"
 - 24:
   - repo: coala-bears
   - link: https://github.com/coala/coala-bears/commit/58a39999a8cc6bf8cf1ce28c5c0745ce39bb8aa0
   - details: "VultureBear: Use the updated Vulture API"
---

### Remove dead code with Vulture automatically

#### Work Done

**vulture**

<br>

1.) In addition to the first line of unused code, Vulture now reports the last 
line of unused code. The results can now also be sorted according to their size.

<br>

2.) Other than the conventional dead code (defined but not used), vulture 
now also finds unsatisfiable conditions in `if/while` statements. Also,
any code appearing after `return`, `break`, `continue` and `raise` statements 
is also reported as dead code.

<br>

3.) Confidence values are now reported with every result. Also, a 
`min_confidence` parameter can be passed to Vulture. It then only reports 
results for which `confidence` > `min_confidence`.

<br>

4.) The Vulture API has been extended and it now exhibits all characteristics 
of dead code, like `confidence`, `first_lineno`, `last_lineno`, `message`, etc. 
It provides user with much more flexibility for automating tests with Vulture.

<br>

5.) Improved whitelist handling process: Every import is now checked
against a corresponding whitelist file (both files must have the same
names), which makes it very easy to add support for new whitelists.

<br>

6.) Vulture is now distributed as a Python `wheel`.

<br>

7.) Allow Vulture to be executed as a package (`python -m vulture`).

<br>

8.) A lot of work was done upstream on Vulture. Afterwards, `VultureBear`
    was refactored to use the new Vulture API. This increased the efficiency
    of the Bear. It is now completely tested and documented in-place.

<br>
