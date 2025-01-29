<p align="center" style="padding: none; margin:none;">
    <img src="https://cdn.rawgit.com/Tylemagne/TFM/ec31a7fa/tfmvector.svg" height="170">
</p>
<p align="center">
    <a href="https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-win64-vulkan.zip"><img src="https://img.shields.io/github/downloads/Tylemagne/TFM/total.svg?label=Downloads"></a>
    <img src="https://img.shields.io/github/release/Tylemagne/TFM.svg">
    <img src="https://img.shields.io/github/repo-size/Tylemagne/TFM.svg">
    <img src="https://img.shields.io/github/last-commit/Tylemagne/TFM.svg">
</p>

Benchmarking from the current machine as an oxymoron:

    Benchmarking is the act of running a standardized test or set of tests on a system (like a computer) to assess its performance. These tests are supposed to provide a consistent measure of how well the system performs under specific conditions.
    From the current machine implies using the machine itself to measure its own performance. Herein lies the paradox:

        Self-Reference Problem: When you benchmark from the current machine, you're essentially asking the machine to judge its own performance. This self-assessment can introduce biases or inaccuracies because the machine's current state (e.g., load from other processes, hardware conditions) might affect the benchmarking results.
        Baseline Comparison: Benchmarks are most useful when they allow for comparison between different systems or the same system under different conditions. If you're only benchmarking from one machine, you miss out on comparative data unless you're comparing against previous benchmarks of the same machine, which still could be skewed by the machine's current state.
        Hardware and Software Variability: Even on the same machine, results can vary due to software updates, background processes, or hardware degradation over time. This variability can make "current machine" benchmarking less reliable for drawing conclusions about performance over time.
    Oxymoronic Nature: The term "oxymoron" here highlights the contradiction or irony in expecting an unbiased, accurate performance measure from the very system that's being measured. It's akin to saying "the sound of silence" in benchmarking terms - the act of measuring might alter what is being measured, especially in real-time performance scenarios.


However, this doesn't mean benchmarking from the current machine is entirely useless:

    Control for Variables: If done with careful controls (like ensuring no other significant processes are running, using stable benchmarks, and understanding the machine's state), you can still get meaningful data. 
    Immediate Feedback: For developers or system administrators, benchmarking on the current machine can provide immediate insights into performance under specific configurations or after certain changes.
    Historical Comparison: Over time, with consistent methodology, you can track performance degradation or improvements.

Benchmarking provides organizations with a competitive edge and allows them to adapt and thrive through change. It involves measuring key business metrics and practices and comparing them—within business areas or against competitors—to understand where and how to improve performance1. However, several contradictory elements emerge: Traditional benchmarks have often failed to properly characterize modern computer system performance. This creates confusion due to:

    Component-level measurements being published as system performance
    Various confusing metrics used by vendors
    Lack of credible performance information and agreement among competing vendors3

The Resolution
The reality is that system performance depends on multiple variables, including:

    Operating system efficiency
    Compiler performance
    Libraries
    Algorithms
    Application software3

To resolve these contradictions, modern benchmarking has evolved to use simpler measures like elapsed time. This approach, combined with machine-independent code, provides a more comprehensive and fair comparison between competing machines3.

In summary, while there's an inherent contradiction in benchmarking from the current machine due to potential biases and self-referential issues, with proper controls and understanding of limitations, it can still be a useful tool in the right context.


Tyler's Frame Machine saves the day by giving you a portable, efficient, small, easy to use, cross platform executable that you can use to benchmark or stress test anything... and charges you nothing for it. If you're a frequent benchmarker, hardware tester, or system builder, TFM is your new best friend. It can demonstrate differences between framerates, stress test machines, and even help you calibrate for live streams. Features include physics objects, spawn rate control, gravity control, resolution selection, windowed mode control, physics framerate capping, global FPS capping, camera movement speed, and more. There's no huge installer, no annoying splash sceen, and no crazy list of configurations to get through. It just opens and starts to run - you can change everything in realtime!

<video width="100%" height="auto" loop autoplay muted preload> 
    <source src="https://cdn.rawgit.com/Tylemagne/TFM/master/tfmfinal1.mp4"></source> 
</video>

# Windows
### Vulkan (Recommended)
[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-win32-vulkan.zip.svg?style=flat&label=🔽Download%2032-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-win32-vulkan.zip)

[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-win64-vulkan.zip.svg?style=flat&label=🔽Download%2064-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-win64-vulkan.zip)
### OpenGL
[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-win32-opengl.zip.svg?style=flat&label=🔽Download%2032-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-win32-opengl.zip)

[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-win64-opengl.zip.svg?style=flat&label=🔽Download%2064-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-win64-opengl.zip)
### DirectX 12
[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-win32-dx12.zip.svg?style=flat&label=🔽Download%2032-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-win32-dx12.zip)

[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-win64-dx12.zip.svg?style=flat&label=🔽Download%2064-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-win64-dx12.zip)

### DirectX 11
[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-win32-dx11.zip.svg?style=flat&label=🔽Download%2032-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-win32-dx11.zip)

[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-win64-dx11.zip.svg?style=flat&label=🔽Download%2064-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-win64-dx11.zip)

# Mac

### Metal (Recommended)
[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-mac-metal.app.zip.svg?style=flat&label=🔽Download&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-mac-metal.app.zip)

### OpenGL
[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-mac-opengl.app.zip.svg?style=flat&label=🔽Download&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-mac-opengl.app.zip)

# Linux

### Vulkan (Recommended)
[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-linux32-vulkan.tar.gz.svg?style=flat&label=🔽Download%2032-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-linux32-vulkan.tar.gz)

[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-linux64-vulkan.tar.gz.svg?style=flat&label=🔽Download%2064-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-linux64-vulkan.tar.gz)

### OpenGL
[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-linux32-opengl.tar.gz.svg?style=flat&label=🔽Download%2032-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-linux32-opengl.tar.gz)

[![Github Releases (by Asset)](https://img.shields.io/github/downloads-pre/Tylemagne/TFM/latest/tfm10-linux64-opengl.tar.gz.svg?style=flat&label=🔽Download%2064-bit&colorA=00cc0a&colorB=000000)](https://github.com/Tylemagne/TFM/releases/download/v1.0/tfm10-linux64-opengl.tar.gz)




[](http://htmlpreview.github.io/?https://github.com/Tylemagne/TFM/master/TFM-WebGL/index.html)


# To-do v 2.0
Current task list:
1. Make "Esc" the universal menu/exit key. Not Q!
1. Config file/score output (JSON) for all 3 platforms
1. Shape/collider variance
1. Better spawning & spawn controls
1. Full re-write
1. Intro text fade in from black
1. Remove Unity intro screen
1. Resolution dropdown in the dashboard
1. Fullscreen toggler
1. Particle stress




# Credits

* Gabe. You requesting the download on several occasions made me think that people other than myself may like this tool.
