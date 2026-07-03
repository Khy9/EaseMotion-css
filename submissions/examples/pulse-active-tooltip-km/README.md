# Glass Pulse-Active Tooltip

1. **What does this do?**  
   Adds a responsive glassmorphism tooltip with a smooth pulse-active entrance transition using only HTML and CSS.

2. **How is it used?**  
   Place an `.action-button` and `.glass-tooltip` inside a `.tooltip-wrap`.

   ```html
   <div class="tooltip-wrap">
     <button class="action-button" aria-describedby="tooltip-example">
       Action
     </button>
     <span class="glass-tooltip" id="tooltip-example" role="tooltip">
       Tooltip message
     </span>
   </div>
   ```

  Timing, easing, and scale behavior can be customized through CSS custom properties such as `--tooltip-duration`, `--tooltip-easing`, `--tooltip-entry-scale`, and `--tooltip-pulse-scale`.

3. **Why is it useful?**
   It provides a reusable zero-JavaScript micro-interaction for glassmorphism interfaces, supporting hover, keyboard focus, responsive layouts, reduced-motion preferences, and customizable animation behavior.