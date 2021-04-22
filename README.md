
# R³school/ELIXIR training: High performance scientific computing using Julia

This repository collects the supporting material for the Julia course.

<img src="media/r3school.svg" alt="R3 school logo" height="64px">   <img src="media/elixir.svg" alt="ELIXIR logo" height="64px">   <img src="media/lih.svg" alt="LIH logo" height="64px">   <img src="media/lcsb.svg" alt="LCSB logo" height="64px">   <img src="media/unilu.svg" alt="Uni.lu logo" height="64px">

## What should I prepare for the course?

If you want to follow the examples, try the stuff interactively and possibly get feedback to your code, you want to install Julia in advance.

- For session 1, you will need just a bare Julia installation (see below).
- For session 2, install the support Jupyter notebooks (also see below).
- For session 3, we will work with distributed computation. If you have a remote computer (e.g. a server) available where you can SSH and run the processes there, you may want to prepare a working SSH connection to it, and install Julia there as well. If you do not have a server, do not worry -- you can do the very same things locally, using multiple Julia processes running on a single machine.

## Installing the necessary tools

Installation of Julia is generally easy and straightforward -- just follow the instructions for your platform here: https://julialang.org/downloads/platform/

You can install the Jupyter support as follows:

1. Start Julia, usually by typing `julia` into the console. If you are greeted by a colorful logo and a green prompt saying `julia>`, it worked out.
2. In Julia interpreter, switch to packaging mode by pressing `]`. The prompt should change color to blue and display versioning information, likely as `(@v1.5) pkg>`.
3. To the packaging prompt, type `add IJulia`. Very likely, you will see some green messages about new packages and IJulia will get installed without problems. If you encounter problems, let us know (ideally send us the red error messages), we will try to help you.

## Course materials

- [Slides for session 1 (basics)](TODO)
- [Data for session 2](session2/) (including the Jupyter notebook and sample files), [pre-rendered slides here](session2/tut01.slides.html) (download the raw HTML and open it in a browser)
- [Slides for session 3 (distributed computing)](TODO)

We will show many small code examples in the Julia interpreter; command history will be published after the course.

## Questions and feedback

Please ask questions anytime during the course. Because the presenters may be watching a different screen than the one with the presentation software, do not worry to ask aloud if we don't notice your virtual "raised hand" at first.

You are invited to leave course feedback here: https://is.gd/Juliaelixir202104
