# SCXN_BoilerplateCSS
 SCXN boilerplate style

Providing handy tools:
- Pop a block open to 100% of the viewport height with .sH ("superHeight")
- .sC ("superCenterer") to quickly "superCenter" a child via flex/Column/Justify-content-center

         <main>
          <section>
           <article class="sH sC">
            <item>
             <p class="w3"> 
              ".w3" sets a warm 81% width.  This text is perfectly centered along x and y axis.  Or...
             </p>
            </item>
           </article>
          </section>
         </main>
            
             
- ... .flex.flexCol.FlexJustifyCenter.FlexAlignCenter spells "superCenterer" on a parent

            <item class="sH flex flexRow FlexJustifyStart FlexAlignCenter ">
             <p class="w3"> 
              Or maybe you'd like your content vertically centered and justified to the left.
             </p>
            </item>

- .compositor ("Compositor") to quickly composite via grid (like and "overlay")
- Combine .compositer with .wash1 for an interesting affect.  Or put .wash1 (wash1-3) on any item to lessen its opacity 76%-27% out of the box
- .lH to set a sensical line-height right away
- .hL1 ("hi-liters" — See what you're doing easily.  Highlight blocks quickly by setting their background colors with styles like .green/.pink/.blue or .hL ("hi-Lite"))
- Pair .poster1 with Bootstrap's jumbotron to create instant billboards
        
         <main class="sH pT1">
          <section clsas="w1 maxed">
           <article class="w1 sH sC jumbotron poster1">
            <item class="outlined wB"
             <p class="w3"> 
              Here's something with pressence whipped out in 2 secs
             </p>
            </item>
           </article>
          </section>
         </main>
             
- Combine a Bootstrap .ms-5 with SCXN's "hard spacing" .pL6 (paddingLeftMax) if Bootstrap margins and padding aren't luxurious enough
- Font and Color variables like var(--f1) or var(--c6) change up a document's appearence fast
- Font swap quickly with .f1 through .f6
- Text sizing tools like .mM .sM and .mB ("mediumMini", "StandardMini" and "mediumBiggie")
- Flip text color and size in a snap
  
        <p>
         Here is an awesome 
          <a href="" class="tW noHover noDecoration"> link
          </a>
         to something great.  It will always be text-color: white; and of course, no backgound or underline (even on mouse events)
        </p>
         
