---
title: Home
layout: home
nav_order: 1
---

Welcome to my Test Doc site
{: .fs-8}
{: .text-center}

aka, also known as T-Doc
{: .fs-7}
{: .text-center}

Test site for Just The Docs.


If you like dark mode, you can:

<button class="btn js-toggle-dark-mode">Try Dark</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Dark Mode?';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Light Mode?';
  }
});
</script>
