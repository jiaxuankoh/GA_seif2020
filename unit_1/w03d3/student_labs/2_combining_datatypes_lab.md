[![General Assembly Logo](/ga_cog.png)](https://generalassemb.ly)

# Avengers, Assemble! (And Other Objects)

![avengers](https://imgur.com/wd9dzYu.png)

#### Learning Objectives

- Combining data types

#### Prerequisites

- JavaScript (objects, arrays)

---

## Getting Started

1. In today's `student_labs` folder, create a file called `the_avengers.js` 

---

## Iron Man 

Given the folowing object... 

```javascript
const ironMan = {
    regularName: 'Anthony Edward "Tony" Stark',
    abilities: ['genius-level intellect', 'proficient scientist and engineer', 'powered armor suit'],
    marvelMovieAppearances: {
        ironMan: true,
        theHulk: true,
        ironManTwo: true,
        thor: false,
        captainAmerica: false,
        theAvengers: true,
        ironManThree: true,
        thorTwo: false,
        captainAmericaTwo: false,
        guardiansOfTheGalaxy: false,
        avengersTwo: true,
        antMan: false,
        captainAmericaThree: true,
        doctorStrange: false,
        guardiansOfTheGalaxyTwo: false,
        spiderManHomecoming: false,
        thorThree: false,
        blackPanther: false,
        avengersThree: true
    },
    jarvisAreYouThere: () => {
       console.log('At your service, sir')
    }
}
```

1. Log Iron Man's third ability
1. Log all of Iron Man's abilities by looping through the array
1. Log whether or not Iron Man appeared in `spiderManHomecoming`
1. Wait, that's not right -- he did appear in that movie! Change the value to true without editing the object itself and log it again to verify it changed
1. Check if jarvis is there by calling on the `jarvisAreYouThere` function 

## Assembling other Avengers 

Create a data structure for `createCaptain` such that...

1. The following code logs `Captain America`

    ```javascript
    console.log(createCaptain().aliases.superheroName)
    ```

1. The following  code logs `peak human strength`

    ```javascript
    console.log(createCaptain().abilities[2])
    ```

1. The following code logs `i can do this all day`

    ```javascript
    console.log(createCaptain().sayPhrase()
    ```

Create a data structure for `blackWidow` such that... 

1. The following code logs `Natalia Alianovna Romanova` 
    
    ```javascript
    console.log(blackWidow.aliases.realName)
    ```
    
1. The following code logs `Natalie Rushman` 
    
     ```javascript
    console.log(blackWidow.aliases.otherNotableAliases[1])
    ```

## Avengers Nested 

Given the following array, loop through it and log just their name. 

```javascript
const theAvengers = [
  { name: 'Tony Stark', superheroName: 'Iron Man'},
  { name: 'Steve Rogers', superheroName: 'Captain America' },
  { name: 'Bruce Banner', superheroName: 'The Hulk'},
  { name: 'Thor' },
  { name: 'Natasha Romanoff', superheroName: 'Black Widow' },
  { name: 'Clint Barton', superheroName: 'Hawkeye' }
]
```

## Other Objects - Intstruments 

Switching gears, let's look at some instrument data! 

```javascript 
const instruments = {
  banjo: ["1920 gibson", "deering", "washburn"],
  guitar: {
    acoustic: ["martin", "taylor", "santa cruz", "gibson"],
    electric: ["fender Strat", "telecaster", "PRS", "languedoc"],
    nylon: ["baldwin", "cordoba"]
  },
  mandolin: ["eastman", "weber", "collings"]
}
```

Given the above object...

1.  Log all of the following: 

    - `telecaster`
    - `santa cruz`
    - `washburn`
    - `weber`

1. Loop through all the _electric_ guitars and log them

1. Add a `vocals` property to the object that includes a list of your favorite singers 

## Other Objects - Garmonbozia 

In early 2017, digital archaeologists discovered a strangest, nonsensical combined data structure. Like in Raiders of the Lost Ark, they refused to look at it directly for fear of melting their faces off.

They called it "Garmonbozia" after the Twin Peaks substance that represents suffering. That substance is creamed corn.

Your mission is to console.log 'creamed corn' from deep within the bizarre structure:

```javascript
const garmonbozia = {
  meltedFace: true,
  wobblyArms: true,
  mysteryMeats: [
    'Schlimmbinooks',
    'blangs',
    { place: 'Akrotiri', treasures: ['Minoan temples', 'volcanoes'] },
    { type: 'Yuck-tops', deliverables: [
      'Nevermind',
      { zone: 'safety-zone' },
      { zone: false, true: true },
      () => {
        return () => {
          return () => {
            return () => {
              return () => {
                return { website: 'Gossipcop.com', what: {
                  offering: 'creamed corn', location: 'dark'
                }
                }
              }
            }
          }
        }
      }
     ]
    }
  ]
}

```

## Hungry for More? - Extra  

1. Want to do more combined datatype drills? Try out [this extra lab](3_extra_methods_lab.md).
1. If you didn't complete the object-ception lab, go back and complete it!
1. Practice your HTML and CSS by trying to recreate the [google homepage](https://www.google.com/)
    - Try recreating the [search view](https://www.google.com/search?ei=htwXXNXTKs6C_wSxm6rgBA&q=hello+world&oq=hello+world) as well! 
1. Sign up for [CodeWars](https://www.codewars.com/) or [HackerRank](https://www.hackerrank.com/) if you haven't already and try out some javascript challenges there! 

---

*Copyright 2018, General Assembly Space. Licensed under [CC-BY-NC-SA, 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)*
