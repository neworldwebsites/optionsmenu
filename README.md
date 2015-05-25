# optionsmenu
Liens href cliquable depuis menu options
---------------------------

    function lienForm() {
        x=document.choix.liste.selectedIndex;
        if(x==0) return;
        url=document.choix.liste.options[x].value;
        parent.location.href=url;}

---------------------------

*code déjà existant mais tellement pratique
