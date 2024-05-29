Descrizione consegna:

Partendo dal markup della versione svolta in js plain, creare uno slider usando Vue.
1) creo un data per la variabile che trovo in javascript:

- const {slides} = Vue

slides({
    data(){
        return{
2) creo un oggetto al suo interno:
             
             - slidesObject:{       
        image: 'img/01.webp',
        title: 'Marvel\'s Spiderman Miles Morale',
        text: 'Experience the rise of Miles Morales as the new hero masters incredible, explosive new powers to become his own Spider-Man.',
             }
        }
    }
})
Bonus:

1 - Aggiungere le thumbnails che si illuminano quando la relativa immagine e' attiva
2-  Aggiungere un evento di click sulle thumbnails per rendere attiva l'immagine relativa