# Convenciones
Las siguientes convenciones ayudan que el desarrollo de aplicaciones en Android sea de manera estructura y facilite el entendimiento del código, que en muchas ocasiones es lo que nos consume más tiempo en un desarrollo.
## Nombrado de Clases

El nombrado de las clases deben seguir el formato CamelCase.

### Activitys
Los Activitys deberan tener su nombre de la siguiente forma  _FuncionPantalla**Activity**_, donde _FuncionPantalla_ es el objetivo de la pantalla que controlara el Activity.

Pantalla     | Nombre
------------ | -------------
Login | LoginActivity
Add student | AddStudentActivity

### Fragments

Para el nombrado de los fragments se debe seguir lo siguiente _FuncionPantalla_**Fragment**, donde _FuncionPantalla_ es el objetivo de la subpantalla que controlara el Fragment.

Pantalla  | Nombre
--------- | -------
View image | ViewImageFragment
Change Name | ChangeNameFragment

### Widgets

Para el nombrado de los widgets se debe seguir lo siguiente _FuncionWidget_**Widget**, donde _FuncionWidget_ es el objetivo del widget.

Funcion  | Nombre
------- | ------
Calendar with events | CalendarWithEventsWidget
Events  | EventsWidget

### Adapters
 
Para el nombrado de los adapters se debe seguir lo siguiente _Coleccion_**Adapter**, donde _Coleccion_ es la lista de elementos que manejara el Adapter.

Coleccion | Nombre
----------|-------
Places  | PlacesAdapter
Flowers | FlowersAdapter

### ViewHolders
Para el nombrado de los view holders se debe seguir lo siguiente _Elemento_**ViewHolder**, donde _Elemento_ es el elemento de la colección que representara el viewHolder.

Elemento | Nombre
---|---
Place | PlaceViewHolder
Flower | FlowerViewHolder

## Nombrado de Recursos
El nombrado de los recursos deben seguir el formato SnakeCase. 
## Activity Layouts
Para el nombrado de los layouts de activities se deben seguir lo siguiente **activity**_funcion_pantalla

Activity | Layout
--- | ---
AddStudentActivity | activity_add_student
DeleteStudentActivity | activity_delete_student

### Fragments Layouts
Para el nombrado de los layouts de fragments se deben seguir lo siguiente **fragment**_funcion_pantalla

Fragment | Layout
--- | ---
ViewProfileFragment | fragment_view_profile
ChangePasswordFragment | fragment_change_password

### Widgets Layouts
Para el nombrado de los layouts de widgets se deben seguir lo siguiente **widget**_funcion_widget

Widget | Layout
--- | ---
EventWidget | widget_event
ProgressWidget | widget_progress

### Items Layouts

Para el nombrado de los layouts de items se deben seguir lo siguiente **item**_elemento

Elemento | Layout
--- | ---
Flower | item_flower
Book | item_book

### Appbar Layouts
Para el nombrado de los layouts de appbar se deben seguir lo siguiente **app_bar**_pantalla

Pantalla | Layout
--- | ---
Main | app_bar_main
Students | app_bar_students

* Cualquier otro layout que no caiga en cualquiera de estos tipos seguira el siguiente formato **layout**_funcion.


