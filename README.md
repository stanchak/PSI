# PSI - Interference Effect

A modern implementation of the iconic interference effect from Future Crew's Second Reality demo (1993). This effect was part of the "Techno" sequence (TECHNO.EXE) and was originally coded in assembly language by PSI (KOEA.ASM). It's considered one of the most impressive visual effects of its time.

## Historical Context

The interference effect was part of the legendary Second Reality demo, which was released by Future Crew in 1993. The demo consisted of 23 separate executables (called "PARTS"), each handling different visual effects. The demo was groundbreaking for its time, pushing the limits of what was possible on the PC platform.

The interference effect specifically was notable for:
- Creating a mesmerizing wave-like interference pattern
- Using clever memory management and bit manipulation
- Achieving smooth animation on limited hardware
- Demonstrating advanced graphics programming techniques
- Being part of the "Techno" sequence, which was one of the most technically impressive parts of the demo

## Technical Implementation

The original effect worked by:
1. Creating a series of circular patterns in memory
2. Rotating and combining these patterns
3. Applying sine wave transformations
4. Managing multiple graphics planes for the interference effect
5. Using custom VGA mode tweaks rather than standard Mode 13h

## Modern Implementation

This is a pure JavaScript implementation that runs directly in the browser. The effect is contained in a single HTML file that uses the HTML5 Canvas API to recreate the iconic interference pattern. The implementation was created using AI, which analyzed the original KOEA.ASM source code to understand the core algorithms and mathematical principles behind the effect, then translated them into modern JavaScript while maintaining the essence of the original implementation.

## Getting Started

Simply open `index.html` in a modern web browser to see the effect in action.

## Credits

Original effect by PSI (Future Crew) in Second Reality (1993)
Modern implementation by [Your Name]

## References

- [Second Reality Code Review by Fabien Sanglard](https://fabiensanglard.net/second_reality/second_reality_parts.php)
- [Original KOEA.ASM source code](https://github.com/fabiensanglard/SecondReality/blob/master/TECHNO/KOEA.ASM) 