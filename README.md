# Screen Space Fluid Rendering
A PIC/FLIP fluid simulation complete with screen space fluid rendering.<br><br>

GPU-based fluid simulation adapted and optimized from https://github.com/dli/fluid (made WebGL optimizations and removed a few redundancies)<br><br>

I used my own homemade SSFR process consisting of performing a 2 pass box blur on the normal buffer as opposed to the traditional method. Also includes a few hacks to made specular reflections simplier(more or less realistic).
