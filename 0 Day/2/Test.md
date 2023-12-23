- creating navbar

1. index.html > body > Comment Navbar
2. index.html > body > G nav class = navbar, navbar-expand-lg, fixed-top, navbar-dark, bg-dark
3. W nav.navbar > div class = container

- creating logo

4. W div.container > a href = "index.html" class = navbar-brand
5. W a.navbar-brand > img src = "images/logo.png" & width:150

- creating toggler or hamburger menu

6. W div.container > button type = "button" & class = navbar-toggler & data-bs-toggle = "collapse" & data-bs-target = "#navbarnNavDropdown" & aria-controls = "navbarnNavDropdown" & aria-expanded = "false" & aria-labels = "Toggle Navigation"
7. W button.navbar-toggler > span class = navbar-toggler-icon

- creating the collapse area

8. W div.container > div class = collapse, navbar-collapse & id = navbarNavDropdown

9. W div.collapse > ul class = navbar-nav, ms-auto

10. W ul.navbar-nav > li class = nav-item > a href= #home & class =nav-link & aria-current = "page" > {Home}
11. W ul.navbar-nav > li class = nav-item > a href= #Discover & class =nav-link > {Discover}
12. W ul.navbar-nav > li class = nav-item > a href= #Summary & class =nav-link > {Summary}
13. W ul.navbar-nav > li class = nav-item > a href= #Takeaways & class =nav-link > {Takeaways}
14. W ul.navbar-nav > li class = nav-item > a href= #Subscribe & class =nav-link > {Subscribe}

- creating icons

15. W div.collapse > span class = nav-item
16. W span.nav-item > span class = fa-stack

- making circle icon

17. W span.fa-stack > a href=# > i.fas-fa-circle.fa-stack-2x

18. W a > i.fab-fa-facebook-f.fa-stack-1x.text-white

- creating twitter icon and circle icon

19. W div.collapse > span class = nav-item
20. W span.nav-item > span class = fa-stack
21. W span.fa-stack > a href=# > i.fas-fa-circle.fa-stack-2x
22. W a > i.fab-fa-twitter.fa-stack-1x.text-white
