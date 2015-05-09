
Sistem de gestiune biblioteca.

############################
Modulul foloseste QR code library care se poate descarca de pe:
http://sourceforge.net/projects/phpqrcode/files/releases/phpqrcode-2010100721_1.1.4.zip/download

Libraria se copiaza la calea: sites/all/libraries/phpqrcode/ al sitelui vostru.	

############################
La instalare se creeaza un user de tip bibliotecar care are drepturile de gestiune a unei biblioteci.
El poate: - sa adauge carti la baza de date
		  - sa modifice statusul cartilor (Availabe, Request, Reserved, Available)
		  - sa trimita mail de notificare catre userul care a reservat cartea
		  - sa genereze QR code de tip poza PNG cu titlul, autorul cartii + userul care a rezervat cartea si data in cara a fost rezervata. 
 
Un user obisnuit poate doar sa vizualizeze tabelul de carti si sa depuna o cerere pentru a rezerva cartea.
Aceasta cerere poate fi procesata de catre bibliotecar.

###########################
Alte informatii
La instalare se creeaza un user cu drepturi de bibliotecar. user: bib password: bib. Se poate modifica ulterior.

Sunt posibile buguri minore care vor fi corectate in viitor.
