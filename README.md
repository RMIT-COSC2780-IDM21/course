# Course on Answer Set Solving in Practice

The main repository integrating the LaTeX beamer-based slides for a MSc class on ASP

## Structure

- mostly implemented by LaTeX' `\part` and `\section` commands
- separate slides with `% ` following by 70 `-`

## Logic

- use `\neg` for (default) negation in view of the logic of Here-and-There (was `\naf` before)

## Style

- use `itemize` environments with `\structure{}` (rather than `description` environment)

## Production

1. uncomment
   1. `\includeonlylecture` and
   2. `{<target>,goodbye,bibliography}`
   in `main.tex`
2. run `latexmk main.tex`
3. rename `main.pdf` into `<target>.pdf`
4. undo above edits, `latexmk main.tex` again
5. produce a release attaching both files
6. link released files in webspace

## Videos

- Format
    - ASP, <target>, Section N: <title>, Mst edition, WiSe2021
- https://youtube.com/c/potassco-live

### List of produced videos

- playlist https://www.youtube.com/playlist?list=PL7DBaibuDD9P5yRyq_Oyn-wuYpBayz_0h

#### Organization

- ASP, organization, section 0: introduction, 1st edition, WiSe2021
  - https://mediaup.uni-potsdam.de/Play/22938

- ASP, organization, section 1: roadmap, 1st edition, WiSe2021
  - https://mediaup.uni-potsdam.de/Play/22939

- ASP, organization, section 2: resources, 1st edition, WiSe2021
  - https://mediaup.uni-potsdam.de/Play/22940

- ASP, organization, section 3: literature, 1st edition, WiSe2021
  - https://mediaup.uni-potsdam.de/Play/22941

- ASP, organization, section 4: systems, 1st edition, WiSe2021
  - https://mediaup.uni-potsdam.de/Play/22942

- ASP, organization, 1st edition, WiSe2021
  - https://youtu.be/wDbXSEjcoKo (HD)
  - https://youtu.be/fUClBdNpyuA (FHD)
  - https://mediaup.uni-potsdam.de/Play/22965

- Release [v1.0.0](https://github.com/potassco-asp-course/course/releases/tag/v1.0.0)

#### Motivation

- ASP, motivation, section 0: introduction, 1st edition, WiSe2021
  - https://youtu.be/_nOPF6eaMeQ
  - https://mediaup.uni-potsdam.de/Play/23002

- ASP, motivation, section 1: declarative problem solving, 1st edition, WiSe2021
  - https://youtu.be/gAOaGs_VjLk (HD)
  - https://youtu.be/H0Qzvii2ZrI (FHD)
  - https://mediaup.uni-potsdam.de/Play/23005

- ASP, motivation, section 2: asp in a nutshell, 1st edition, WiSe2021
  - https://youtu.be/y6K7gLbuHhY
  - https://mediaup.uni-potsdam.de/Play/23055

- ASP, motivation, section 3: evolution, 1st edition, WiSe2021
  - https://youtu.be/UdRHpX_CiUM (HD)
  - https://youtu.be/Lc2se6bj-Jo (FHD)
  - https://mediaup.uni-potsdam.de/Play/23101

- ASP, motivation, section 4: foundations, 1st edition, WiSe2021
  - https://youtu.be/HjxyY1mWT7c (HD)
  - https://youtu.be/h10ot9OyM38 (FHD)
  - https://mediaup.uni-potsdam.de/Play/23103

- ASP, motivation, section 5: workflow, 1st edition, WiSe2021
  - https://youtu.be/4ZaVI36s6hs
  - https://mediaup.uni-potsdam.de/Play/23104

- ASP, motivation, section 6: engine, 1st edition, WiSe2021
  - https://youtu.be/hOMIB9zdlCc (HD)
  - https://youtu.be/WX-53B9Pq54 (FHD)
  - https://mediaup.uni-potsdam.de/Play/23105

- ASP, motivation, section 7: usage, 1st edition, WiSe2021
  - https://youtu.be/KVVXFd8CuGM
  - https://mediaup.uni-potsdam.de/Play/23106

- ASP, motivation, section 8: summary, 1st edition, WiSe2021
  - https://youtu.be/R5yyiyb3edg
  - https://mediaup.uni-potsdam.de/Play/23107

- Release [v1.1.0](https://github.com/potassco-asp-course/course/releases/tag/v1.1.0)

#### Introduction

- ASP, introduction, section 0: introduction, 1st edition, WiSe2021
  - https://youtu.be/_9dlDE1OsQA
  - https://mediaup.uni-potsdam.de/Play/23477

- ASP, introduction, section 1: syntax, 1st edition, WiSe2021
  - https://youtu.be/d2FzfU_L2R8 (HD)
  - https://youtu.be/FKpmMIgsQhM (FHD)
  - https://mediaup.uni-potsdam.de/Play/23491

- ASP, introduction, section 2: semantics, part I, 1st edition, WiSe2021
  - https://youtu.be/Vb7rV6c7jAk (HD)
  - https://youtu.be/Fmj0KJL_i04 (FHD)
  - https://mediaup.uni-potsdam.de/Play/23594

- ASP, introduction, section 2: semantics, part II, 1st edition, WiSe2021
  - https://youtu.be/nTGPLXhwI7s (HD)
  - https://youtu.be/gN6WHEweXOg (FHD)
  - https://mediaup.uni-potsdam.de/Play/23600

- ASP, introduction, section 2: semantics, part III, 1st edition, WiSe2021
  - https://youtu.be/2BpBHMoFAAQ (HD)
  - https://youtu.be/5_TyvPf8G7Q (FHD)
  - https://mediaup.uni-potsdam.de/Play/23657

- ASP, introduction, section 2: semantics, part IV, 1st edition, WiSe2021
  - https://youtu.be/1rdwKemok7Y (HD)
  - https://youtu.be/T_AqkLQHxhw (FHD)
  - https://mediaup.uni-potsdam.de/Play/23659

- ASP, introduction, section 2: semantics, part V, 1st edition, WiSe2021
  - https://youtu.be/ehfTpFHSMnY (HD)
  - https://youtu.be/CWDA5QqEpf4 (FHD)
  - https://mediaup.uni-potsdam.de/Play/23672

- **in progress**
