C++ Windows app Runner game, created for a CS course assignment.

Technology
C++ & MFC - MFC has been used due to demand by the course's head.

App Creation Motive
We had to create a windows app using MFC C++ and the project must've contained some graphical presentations, most of the students decided to create a basic paint app (and the course's head did teach some techniques in this direction) but because of the paint, un-genuine implementation, we decided to create a runner game. no special animation/gif loader lib was used due to the restrictions, so we did have to implement such a mechanism by ourselves.

Game And Graphics View

![DodgerExample](https://user-images.githubusercontent.com/91319947/139396599-ce761ca7-8efd-41f2-96ef-93a922e2453f.gif)
![Game Over Example](https://user-images.githubusercontent.com/91319947/139396608-0bec5b1f-7cba-404f-ba2a-04ef403a7dd9.gif)


Actually, although MFC is old-fashion, the implementation was kind of fun, I can tell.

About The Game
The idea is to dodge obstacles. You can create players and load icons for it, gain higher scores than your friends, and so on. The obstacle's random but yet character aimed behavior makes the game kind of harder than it seems in the first place, but yet enjoyable. And the competition between the obstacles and of course your's or your friends' high score makes it kind of addictive game.

Game Setup (for those who just want to play)
You can find it between the repo files, under the name: Dodger Setup.zip

Credits:
My Partner: Shahar Tal.
Thanks to Nintendo & Game Freak for those great characters (pokemon characters images).
CMemDC license is inside the project files, under the FlickerFreeDC.h file, thanks for all of its collaborators.
Thanks to jrsoftware for making Inno Setup, a great third-party app for creating an installer for executable files and its resource files.
