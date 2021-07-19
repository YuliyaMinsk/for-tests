# Ulyana Ihnatchyk
## Contacts:
* e-mail: uliana.ignatchik@gmail.com
* vk: ul_gemoglobin
## Personal information:
My motto:
> Not all wheels are invented yet.
> Richard Branson
So I'm always open to the idea of developing both hard and soft skills. I can characterize myself as an ambitious problem solver with a passion for online businesses, and who would like to join a team of like-minded developers. 
### Strength:
* Always positive, regardless of the challenge ahead.
* Good communication and personal-interaction skills.
* Willingness to develop.
* Enthusiastic approach to work.
* Need little time to learn and adaptate.
## Skills:
* HTML
* CSS
* JavaScript
## Code examples:

JavaScript:
```javascript

function place (coordinate) {
                return Math.floor(Math.random() * coordinate);
            }

            function receiveDistance (event, target) {
                return Math.sqrt((target.x - event.offsetX) * (target.x - event.offsetX) + (target.y - event.offsetY) * (target.y - event.offsetY));
            }

            function editMessage (dist) {
                if (dist < 8 && dist !== null) {
               alert("Клад найден! Количество попыток: " + clicks);
               contin = confirm ("Желаете повторить?");
               
               if (contin === true) {
                   clicks = 0;
                target = {
                "x": place(width),
                "y": place(height)
            }
               }
                }
                if (dist < 10) {
                    return "Ну точно где-то рядом";
                }
                if (dist < 20) {
                    return "Ооочень горячо";
                }
                if (dist < 40) {
                    return "Горячо";
                }
                if (dist < 80) {
                    return "Тепло";
                }
                if (dist < 160) {
                    return "Холодно";
                }
                if (dist < 320) {
                    return "Очень холодно";
                }
                else {
                    return "Холоднее и не придумаешь"
                }
            }

            var height = 600;
            var width = 600;
            var target = {
                "x": place(width),
                "y": place(height)
            }

            var clicks = 0;
            var dist = null;
            var finalMessage = null;
            var contin = null;

            $("#map").click(function (event) {
                clicks++;
                dist = receiveDistance(event, target);
                finalMessage = editMessage(dist);
                $("#message").text(finalMessage);
            })
            
`` ''
## Work experience
I haven't experienced in working with real projects yet, but I'm always ready.
## Education
I graduated from kindergarten and basic scholl. Now I'm styding at secondary school. Also I've got education in national children's technopark where I've mastered the robotics course program. There I used to program using C language.
## English
B2
