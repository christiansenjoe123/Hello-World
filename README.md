# Hello-World
// eJOKE (c) JOE
/////////////////////////////////////////////////////////////////////////////
//first questions asked about what you want to do
do {
var yn = prompt("do you want to hear a joke?", "yes");
    if (yn === "yes") {
        var jt = prompt("Select joke type: Joke, Q and A, Knock Knock", "Joke type (please match case)");
    } else if (yn === "no") {
        window.alert("Okay, that's fine... bye");
    } else {
        window.alert("Sorry... I didn't catch that. Please try again");
    }
}    
while(yn === "no");
///////////////////////////////////////////////////////////////////////////// 
//Joke type: Joke
if (jt === "Joke") {
    window.alert("My Grandpa said, 'Your generation relies too much on technology!'  I replied, 'No, your generation relies too much on technology!'  Then I unplugged his life support.");
}
//use the below when we enter more jokes into this catigory
/*if (jt === "Joke") {
    var rJ = math.random();
        if (rJ
}*/
/////////////////////////////////////////////////////////////////////////////
//Joke type: Q and A 
if (jt === "Q and A") {
    var rQA = Math.random()
        if (rQA < .1666666667) { //#1
            var QA1 = prompt("What do you call security guards outside Samsung shops?", "IDK");
        if (QA1 === "Guardians of the Galaxy") {
            window.alert("Wow I think... actually I'm a computer I can't think... but that's beside the point... I 'think' you cheated");
}       else {
            window.alert("Guardians of the Galaxy");
            }  
    } else if (rQA <= .3333333333) { //#2
            var QA2 = prompt("What do you call an alligator in a vest?", "IDK");
        if (QA2 === "An Investigator") {
            window.alert("Wow I think... actually I'm a computer I can't think... but that's beside the point... I 'think' you cheated");
}        else {
            window.alert("An Investigator");
            }  
    } else if (rQA <= .5) { //#3
            var QA3 = prompt("What's the difference between a guitar and a fish?", "IDK");
        if (QA3 === "You can't tuna fish") {
            window.alert("Wow I think... actually I'm a computer I can't think... but that's beside the point... I 'think' you cheated");
       } else {
            window.alert("You can't tuna fish");
            }  
        
    } else if (rQA <= .6666666667) { //#4
            var QA4 = prompt("Did you hear about the race between the lettuce and the tomato?", "IDK");
        if (QA4 === "The lettuce was a 'head' and the tomato was trying to 'ketchup'!") {
            window.alert("Wow I think... actually I'm a computer I can't think... but that's beside the point... I 'think' you cheated");
      } else {
            window.alert("The lettuce was a 'head' and the tomato was trying to 'ketchup'!");
            }  
        
    } else if (rQA <= .8333333334) { //#5
            var QA5 = prompt("Why can't you give Elsa a balloon?", "IDK");
        if (QA5 === "Because she will 'Let it go'!") {
            window.alert("Wow I think... actually I'm a computer I can't think... but that's beside the point... I 'think' you cheated");
       } else {
            window.alert("Because she will 'Let it go'!");
            }  
        
    } else if (rQA <= 1) { //#6
            var QA6 = prompt("What do you call a fake noodle?", "IDK");
        if (QA6 === "An Impasta") {
            window.alert("Wow I think... actually I'm a computer I can't think... but that's beside the point... I 'think' you cheated");
       } else {
            window.alert("An Impasta");
       }  
        
    } 

}

//1= rQA < .1666666667
//2= rQA <= .3333333333
//3= rQA <= .5
//4= rQA <= .6666666667
//5= rQA <= .8333333334
//6= rQA <= 1
/////////////////////////////////////////////////////////////////////////////
//Joke type Knock Knock
else if (jt === "Knock Knock") {
    var rKK = Math.random()
        if (rKK < .1666666667) { //#1
            var KK1a = prompt("Knock Knock", "who's there");
                if (KK1a === "who's there") {
                    var KK1b = prompt("canoe", "canoe, who?");
                        if (KK1b === "canoe, who?") {
                            var KK1c = window.alert("canoe help me with my homework?");
                            }
                        }
        } else if (rKK <= .3333333333) { //#2
            var KK2a = prompt("Knock Knock", "who's there");
                if (KK2a === "who's there") {
                    var KK2b = prompt("orange", "orange who?");
                        if (KK2b === "orange who?") {
                            var KK2c = window.alert("orange you going to let me in?");
                            }
                        }
        } else if (rKK <= .5) { //#3
            var KK3a = prompt("Knock Knock", "who's there");
                if (KK3a === "who's there") {
                    var KK3b = prompt("anee", "anee, who?");
                        if (KK3b === "anee, who?") {
                            var KK3c = window.alert("anee one you like!");
                            }
                        }
        } else if (rKK <= .6666666667) { //#4
            var KK4a = prompt("Knock Knock", "who's there");
                if (KK4a === "who's there") {
                    var KK4b = prompt("iva", "iva, who?");
                        if (KK4b === "iva, who?") {
                            var KK4c = window.alert("I've a sore hand from knocking!");
                            }
                        }
        } else if (rKK <= .8333333334) { //#5
            var KK5a = prompt("Knock Knock", "who's there");
                if (KK5a === "who's there") {
                    var KK5b = prompt("dozen", "dozen, who?");
                        if (KK5b === "dozen, who?") {
                            var KK5c = window.alert("dozen anybody want to let me in?");
                            }
                        }
        } else if (rKK <= 1) { //#6
            var KK6a = prompt("Knock Knock", "who's there");
                if (KK6a === "who's there") {
                    var KK6b = prompt("avenue", "avenue, who?");
                        if (KK6b === "avenue, who?") {
                            var KK6c = window.alert("avenue knocked on this door before?");
                            }
                        }
        }
    }
//1= rKK < .1666666667
//2= rKK <= .3333333333
//3= rKK <= .5
//4= rKK <= .6666666667
//5= rKK <= .8333333334
//6= rKK <= 1
