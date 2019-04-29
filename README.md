# ionrating
rating stars - componente customizado para avaliações

# ionic g component IonRating

Alexandre Justino

https://www.youtube.com/watch?v=WiuFgIyCV0s&list=WL&index=88&t=0s

\-src

--components

---ion-rating

----ion-rating.html

----ion-rating.scss

----ion-ratin.ts

---components.module.ts

        <ion-card-header>
            <ion-rating [Reading]="false" [valor]="project.ratingvalue" (ionClick)="numberstars($event)"></ion-rating>
        </ion-card-header>
