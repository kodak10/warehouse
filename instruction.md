pour la declaration des routes dans le fichier web.php se fera de la façon suivante :
Route::get('/', function () {
    return view('visitor/index');
})->name('home');

veuillez à utiliser l'attribut name('nom_de_la_route') permet de faciliter la maintenance du site.

le dossier visitor est le dossier qui contiendra le front-end du site.
le dossier admin est le dossier qui contiendra le back-end du site.

<<<<<les 2 dossiers énnumérer ci-dessous contiendront en fait les vues du front-end et du back-end de façon respective. cela ne concerne en rien les controllers et le modèles>>>>>>
