# Information Security Administration - Final Prep Dashboard 🎓

A modern, responsive, and highly interactive exam preparation dashboard built for a last-minute, high-intensity study sprint. This project organizes the Information Security Administration curriculum into a focused 2-day study plan.

## 🌟 Features

- **🍎 Premium Apple-Style UI**: Employs modern glassmorphism aesthetics, mesh gradients, translucent cards, and smooth CSS transitions.
- **🌙 Native Dark Mode**: Optimized for late-night studying with low-strain colors and high-contrast text.
- **📱 Fully Responsive**: Flawlessly adapts to any screen size—whether you are using a PC, Tablet, or Mobile Phone.
- **💾 Local Storage Memory**: Your progress is instantly saved to your browser's local storage. You can safely close the tab or reboot your device, and your checkmarks will still be there.
- **📊 Real-time Progress Tracking**: Interactive circular checkboxes instantly update the overall progress bars and dashboard statistics without requiring a page refresh.
- **🧠 Smart Carry-Over**: Remembers the exact day you started studying. If the date rolls over and you haven't finished your "Day 1" tasks, they are automatically migrated to your Day 2 schedule and badged as "Missed Yesterday!".

## 🚀 How to Use & Deploy

This project is entirely self-contained within **a single HTML file** with no external dependencies (No React, No Tailwind, No NPM required).

### Local Usage
1. Simply double-click on `exam_prep_plan_ISA.html`.
2. It will open directly in your default web browser.

### GitHub Pages Deployment
Since everything is contained in standard HTML, CSS, and JS, deployment takes less than a minute:
1. Initialize a Git repository and push this folder to a new GitHub repository.
2. In your GitHub repository, go to **Settings** > **Pages**.
3. Under **Build and deployment**, set the Source to `Deploy from a branch`.
4. Select your `main` or `master` branch and hit **Save**.
5. Within 1-2 minutes, your dashboard will be live at `https://[your-username].github.io/[repo-name]/exam_prep_plan_ISA.html`.

## 🛠️ Customization

If you want to edit the curriculum, priorities, or study time estimates, scroll to the bottom of the `exam_prep_plan_ISA.html` file and modify the `allTopics` JavaScript array. The interface and progress math will automatically adapt to any new topics you add!
