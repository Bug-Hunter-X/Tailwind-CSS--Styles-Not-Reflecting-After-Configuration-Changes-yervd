# Tailwind CSS Styles Not Rendering After Configuration Changes

This repository demonstrates a common issue in Tailwind CSS where custom styles fail to apply after making changes to the `tailwind.config.js` file.  The problem stems from a failure to rebuild the CSS after modifications. This results in the absence of the expected styles in the rendered HTML.  The solution involves ensuring the project's build process is executed post configuration changes to incorporate the new styles.

## Problem
The provided code initially lacks the expected red background because the CSS hasn't been recompiled to reflect the configuration settings. This is a common pitfall for developers new to Tailwind CSS.