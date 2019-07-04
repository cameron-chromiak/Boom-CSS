

  # B💥💥M
  # CSS
  #
  ### A light-weight css framework with all the essentials. B💥💥M uses Bootstrap-inspired class names to help keep things natural. The purpose of BOOM is to eliminate the need for writing common CSS classes for every project. You find only essential CSS classes.

  #
## Getting Started:
### Add the following CDN:
```
  <link rel="stylesheet" href="https://raw.githubusercontent.com/cameron-chromiak/Boom-CSS/master/index.css">
  ```
  ##### Full repository can be found [here](https://github.com/cameron-chromiak/Boom-CSS)

#
### How to use:
#

#### Spacing
To anyone who's used BootStrap before, this is exactly the same. Sizes range between 1-6, and are given in rems.
`.m-1`-->`margin: 1rem;`  
`.mt-3`-->`margin-top: 3rem;`  
`.ml-5`-->`margin-left: 4rem;`  

###### The same with padding:
`.p-1`-->`padding: 1rem;`  
`.pr-6`-->`padding-right: 6rem;`  

#### Fonts
  Fonts come in sizes raging from xs to xl, along with h-sized fonts that range bewtween 1 and 6. Font weights are also inncluded.

`.h1`-->`font-size: 4.8rem;`
`.h6`-->`font-size: 2.3rem;`  

`.fs-lg`-->`font-size: 2.0rem;`  
`.fs-md`-->`{font-size: 1.6rem;`  
`.fs-sm`-->`font-size: 1.2rem;`  
`.fs-xs`-->`font-size: 0.8rem;`  

`.fw-heavy`-->`font-weight: 700;`  
`.fw-light`-->`font-weight: 300;`  

  #### Display Properties
The display properties are here to easily apply flex-styles to individual elements.

`.flex-row` has the following properties:
  ```{
  display: flex;
  flex-direction: row;
}
```
`.flex-col-reverse` You may have guessed.
```
{
  display: flex;
  flex-direction: column-reverse;
}
```
`.justify-conter`-->`justify-content: center;`
`.space-around`-->`justify-content: space-around;`

## Cards
 Boom uses a grid system to maintain any card fields. To make use of this grid all `.card` elementd should be wrapped by a `.card-container`

 ```
   <div class="card-container">
    <div class="card">
      <div class="card-title">Title</div>
      <img class="card-img"src="https://images.unsplash.com/photo-1513584684374-8bab748fbf90?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&w=1000&q=80" alt="">
      <div class="card-content">
        <p> Lorem ipsum dolor sit amet, consectetur
          adipisicing elit, sed do eiusmod tempor
           sint occaecat cupidatat non proident
           ,sunt in culpa qui officia deserunt
           mollit anim id est laborum15
         </p>
       </div>
       <div class="card-meta">
          2:22pm
       </div>
    </div>
  </div>
 ```

#### Bonus:
###### Included in every BOOM CSS link is a free CSS style reset. You're welcome.
