+++
title = "Ecosistemi coordinati di robot programmabili"
outputs = ["Reveal"]
+++

<script>
  $(document).ready(function() {
    
   function animaImmagine(idName) {
        $(idName).animate({
            width: '+=50px',
            height: '+=50px'
        }, 1000, function() {
            $(idName).animate({
                width: '-=50px',
                height: '-=50px'
            }, 1000, function() {
                // Ripeti l'animazione in loop
                animaImmagine(idName);
            });
        });
    }

    animaImmagine("#robot1");
    animaImmagine("#robot2");

  });

  
</script>

# Ecosistemi coordinati <br/>di robot programmabili


<img src="example-background.svg" width="25%" class="my-5" />

<div style="font-size: 0.8em">
Gianluca Aguzzi, Martina Baiardi, Roberto Casadei, <br/>
Davide Domini, Nicolas Farabegoli, Danilo Pianini, Mirko Viroli
</div>

<img src="images/robot-1.svg" width="15%" id="robot1" style="position: absolute; top: 0%; left: 2%;" />
<img src="images/robot-2.svg" width="10%" id="robot2" style="position: absolute; bottom: 0%; right: 8%;" />

---



{{% multicol %}}{{% col class="text-right" %}}

<img src="images/animal-1.jpg" width="700px" style="margin-right: 18px"/>

{{% /col %}}{{% col class="text-left" %}}

<img src="images/animal-2.webp" width="700px" style="margin-left: 18px"/>

{{% /col %}}{{% /multicol %}}

{{% multicol %}}{{% col class="text-right" %}}

<img src="images/animal-3.jpg" width="700px" style="margin-right: 18px"/>


{{% /col %}}{{% col class="text-left" %}}

<img src="images/image-4.jpeg" width="700px" style="margin-left: 18px" />

{{% /col %}}{{% /multicol %}}


    
---


<iframe width="100%" height="1000px" loading="eager" autoplay="true" src="https://lumasky.show/wp-content/uploads/personal/oblozhka2.html?autoplay=1&controls=0&loop=1&modestbranding=1&mute=1&showinfo=0" ></iframe> 

---

<iframe width="100%" height="900px" loading="eager" autoplay="true" src="https://www.youtube.com/embed/qy4_3qJbLeA?si=P2jwvfj6-YR9CujO?autoplay=1" frameborder="0"></iframe>


---

## Una piccola dimostrazione

{{% multicol %}}{{% col class="text-center" %}}

<img src="images/robot.png" width="80%"/>

{{% /col %}}{{% col class="text-left" %}}

Abbiamo un robot speciale denominato **leader**, che *guida* gli altri, ottenendo un **sistema auto-organizzante**:

1. Tutti i robot puntano verso la stessa direzione
2. Tutti i robot puntano verso il leader
3. I robot "danzano" in modo coordinato, raggiungendo la stessa direzione puntata dal leader
4. Formazioni di semplici strutture: tutti i robot si dispongono in linea e in cerchio rispetto al leader.

{{% /col %}}{{% /multicol %}}
