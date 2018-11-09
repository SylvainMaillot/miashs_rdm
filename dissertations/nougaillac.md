

**DISSERTATION**

**En quoi l&#39;interop�rabilit� est-elle un �l�ment essentiel pour l&#39;Open Data et dans le domaine de la data science ?**

Nous allons commencer par d�finir ce qu&#39;est l&#39;interop�rabilit� au sens g�n�ral puis plus sp�cifiquement au domaine de l&#39;informatique. Nous expliquerons pourquoi le web est un bon exemple de l&#39;interop�rabilit� et ce que cela lui apporte.

Ensuite nous aborderons la question de l&#39;open data et nous dirons pourquoi l&#39;interop�rabilit� est essentielle dans le d�veloppement de celui-ci et en quoi cela am�liore les performances de la data science.

On parle d&#39;interop�rabilit� lorsqu&#39;on a au moins deux syst�mes capables de communiquer et de s&#39;�changer des donn�es sans effort de la part de l&#39;un ou de l&#39;autre pour se comprendre. L&#39;interop�rabilit� se retrouve dans d&#39;innombrables domaines tels que les r�seaux routiers, ferroviaires, a�riens, la t�l�phonie, les forces arm�es,�.

Par exemple, l&#39;interop�rabilit� dans la t�l�phonie permet � deux personnes de se parler au t�l�phone sans pour autant qu&#39;elles aient le m�me op�rateur ni la m�me marque de t�l�phone. Cela sous-entend que des r�seaux t�l�phoniques h�t�rog�nes (g�r�s par les op�rateurs diff�rents) et des mat�riels divers respectent les m�mes normes de communication (donn�es, signaux, c�ble, courant, ...). En informatique, l&#39;interop�rabilit� repose donc sur la cr�ation et le respect de standards d�crivant des formats et des r�gles d&#39;�change des donn�es � travers ces formats. � l&#39;oppos�, un frein � l&#39;interop�rabilit� est l&#39;utilisation d&#39;un format de fichier propri�taire par un logiciel qui emp�che son exploitation par un utilisateur tiers qui ne connaitrait pas ce format.

Le web (raccourci de World Wide Web) a �t� cr�� � la fin des ann�es 80 pour permettre d&#39;�changer des informations sous forme de pages directement consultables via un outil de navigation (client l�ger) depuis son ordinateur.

Le web est une application d&#39;internet qui lui est un r�seau de r�seaux, qui permet donc de relier un ensemble de machines � travers le monde. L&#39;id�e est de pouvoir passer d&#39;une page (principe de l&#39;hyper texte) � une autre sans avoir � les stocker sur sa propre machine ni m�me de savoir o� elles sont h�berg�es. Chaque page est identifi�e par une adresse unique (URI) accessible depuis n&#39;importe o�.

**L&#39;objectif est de n&#39;avoir qu&#39;un seul web partout et pour tous.**

Les communications entre le navigateur de l&#39;utilisateur et le serveur qui fournit l&#39;information sont g�r�es par le protocole HTTP.

Il a donc fallu cr�er un format de page lisible par l&#39;ensemble des navigateurs (HTML), un protocole de communication (HTTP) et un syst�me d&#39;identification des pages ou ressources (URI) pour permettre � tous les utilisateurs quel que soit leur ordinateur, leur syst�me d&#39;exploitation et leur navigateur de pourvoir consulter les m�mes informations disponibles � travers le web.

Cet ensemble de r�gles est d�finie par le W3C (World Wide Web Consortium) qui est une association ou organisme de standardisation charg� de promouvoir la compatibilit� des technologies du web telles que HTML, XML, RDF, SPARQL,�

Les d�veloppeurs des navigateurs doivent suivre ces recommandations et faire �voluer en permanence leur application afin qu&#39;elles restent compatibles avec ces technologies.

A l&#39;origine on parlait de web statique car il permettait seulement de diffuser des pages d&#39;informations statiques sur lesquelles les utilisateurs ne pouvaient pas agir.  Est apparu ensuite le web dynamique qui permet une interaction entre l&#39;utilisateur et le serveur faisant �voluer les donn�es du web (apparition de blog, forum, formulaire de saisie,�). On parle ensuite de web de donn�es o� les donn�es sont r�utilisables comme dans une base de donn�es et de web s�mantique dans lequel on y rajoute sa description et les diff�rentes relations existantes.

L&#39;Open Data est une pratique qui consiste � publier des donn�es num�riques publiques afin de les rendre accessibles aux usagers � travers le web. Il s&#39;appuie sur les m�canismes du web de donn�es qui consid�re les donn�es comme si elles �taient dans une base de donn�es avec la dimension de r�utilisation puisque le principal objectif de l&#39;open data est d&#39;�tre libre de pouvoir la r�utiliser.

Malgr� une l�gislation mise en place en Europe et dans certains pays qui imposent aux collectivit�s et organismes publics de publier certaines donn�es, dans la pratique on se rend vite compte que ce n&#39;est qu&#39;un leurre. En effet, pour qu&#39;une donn�e soit ouverte, il faut qu&#39;elle soit accessible, sans authentification, dans un format exploitable, document�e et surtout actualis�e. Tr�s peu le sont en r�alit�. Apr�s de nombreuses heures � rechercher des donn�es dans divers domaines on trouve facilement des donn�es exportables au format csv (par exemple) mais tr�s peu d&#39;API qui permettent d&#39;y acc�der directement sans authentification.

Les API sont essentielles car elles permettent d&#39;acc�der automatiquement aux donn�es externes mises � disposition par un fournisseur. Une API est un programme qui sert d&#39;interface entre l&#39;application qui m�lange les donn�es (Mashup) et les donn�es ext�rieures fournies. Pour �tre performante une API doit �tre utilisable par le plus grand nombre.

L&#39;interop�rabilit� est l&#39;�l�ment cl� dans ce cadre d&#39;utilisation car les donn�es fournies doivent �tre dans un format normalis� (JSON, XML), clairement d�crites pour �tre compr�hensibles (interop�rabilit� s�mantique : XML RDF), et document�es.

La Data science qui consiste � extraire des donn�es afin de les analyser est un m�lange entre la statistique inf�rentielle, le d�veloppement d&#39;algorithme et la technologie, dont l&#39;objectif est la r�solution de probl�mes analytiques complexes. Elle prend un essor depuis plusieurs ann�es gr�ce au d�veloppement du Big Data qui permet le traitement d&#39;un grand volume de donn�es.

Or plus une donn�e est compl�te, riche et pertinente plus elle sera probante pour le data scientist.

Le m�tier de data scientist consiste avant tout � s&#39;approprier le sujet et la probl�matique, c&#39;est-�-dire le domaine m�tier. Ensuite il doit explorer les donn�es qui sont disponibles, par exemple dans les datawarehouse de l&#39;entreprise, via les services web internes ou externes, les chercher dans l&#39;open data ou �ventuellement les acheter. Il est possible aussi de croiser les donn�es de diff�rentes sources dispers�es.

Les donn�es recueillies permettront ainsi de cr�er des mod�les d&#39;analyse et des algorithmes pour ainsi d�gager des tendances, �laborer des profils, faire des pr�dictions� Cela apporte une r�elle valeur ajout�e � l&#39;entreprise dans la prise de d�cision dans de nombreux domaines.



En conclusion, je pourrai dire qu&#39;un gros travail est � faire aupr�s des organisations publiques et des collectivit�s afin qu&#39;elles respectent le cadre l�gal de l&#39;open data. En effet, seules 8% des collectivit�s publient des donn�es num�riques. Les multiples plaintes aupr�s de la CADA (commission d&#39;acc�s aux documents administratifs) t�moignent du retard dans la mise en place de l&#39;open data dans l&#39;administration fran�aise.

Il ne suffit pas de mettre � disposition des informations sous forme num�rique (exemple photographie d&#39;un document manuscrit enregistr� au format pdf) pour croire que l&#39;on fait de l&#39;open data !

Une des perspectives de ma future carri�re de data scientist au sein de l&#39;Education Nationale sera d&#39;acculturer les d�cideurs et surtout les d�tenteurs de la donn�e num�rique aux enjeux de l&#39;open data.

