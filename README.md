# UAIC-UD
Nr.crt.	UAICtb	POS	lemma	head UAICtb	UD	example	head formatUD	Observații
1	a.adj.	A		subst	amod	casă verde	subst	
	a.adj.	D		subst	det	acest coteț	subst	
	a.adj.	M		subst	nummod	trei lulele	subst	
2	a.adv.			subst	advmod	ziua de ieri	subst	nu apare la UD ca determinant nominal
3	ap.			subst	appos	el, vărul	subst	e posibil să apară și appos care determină alte părți de vorbire dar noi nu avem în vechiul treebank decât subordonate de subst
	ap.			sbj.	expl	Ion a venit și el	predicat	dacă este vorba de subiectul repetat, trebuie adnotat de experți; nu avem altă marcă decât dependența de subiect și eventual a.adv.=și
4	a.pron.	P cu prep.		subst	nmod	întâlnire cu dânșii	subst	atribut prepozițional
	a.pron.	P în caz.oblic		subst	nmod:poss	sfatul acestuia	subst	atribut genitival
	a.pron.	Px oblic neacc		subst	nmod:poss	și-a spart capul	verb	dativul posesiv
	a.pron.	Pp oblic neacc		subst	nmod:poss	capu-i spart	verb	dativul posesiv
5	a.subst.	N cu prep		subst	nmod	ora de citire	subst	atribut prepozițional
	a.subst.	N caz obilc		subst	nmod:poss	casa piticilor	subst	artibut genitival
	a.subst.	Np caz drept fără prep		subst	name	Radu Ionescu	subst	au fost adnotate așa numele formate din mai multe cuvinte
	a.subst.	Np caz drept fără prep, cu virgulă		subst	list	Rosembery Road, Bilingham; Graham Watson, 20 de ani	subst	adrese, date între care nu sunt marcate relații sintactice
	a.subst.	M		subst	nummod	trei mii de ani	subst	unele numerale cu aspect de substantiv au fost adnotate ca a.subst. în UAICtb.
6	aux.		fi	verb	auxpass	era biruit	verb	
	aux.		fi	verb	aux	să fi greșit	verb	trebuie văzut de un expert, există cazuri când fi nu e pasiv
	aux.		altul decât fi	verb	aux	va termina	verb	trebuie adnotat manual arborescent auxiliarul auziliarului pasiv
7	a.vb.			subst	acl	datorie de a citi; datoria să citești	subst	sigla a.vb. se punea pe relația dintre subst regent și elementul de relație subordonator. sigla acl se pune pe relația dintre vb. regent al clausei si substantivul pe care îl determină.
8	c.ag.	cuvânt		verb pasiv	nmod:agent	chemat de prieteni	verb pasiv	???nu este o relație facultativă ci necesară
	c.ag.	clause		verb pasiv	advcl:agent	chemat de cine are nevoie	verb pasiv	nu este o relație facultativă ci necesară
9	c.c.conc.	R		verb	advmod		verb	transpunerea c.c... trebuie făcută cu mutarea informației într-un alt strat, deci nu înainte de a schimba formatul xml-ului
	c.c.conc.	N		verb	nmod	cu toate greutățile a reușit	verb	de fapt aici ar trebui folosită nmod așa era concepută în UD. Dacă o folosim și aici, și la complementul prepozițional, iese o varză! Nu mai putem adnota caracterul intranzitiv al verbului nicicum! Poate totuși ne hotărâm să adnotăm c.prep ca pe un iobj și propoziția respectivă cu ccomp și nu mai avem nevoie de sigla nemaiauzită advcl:pmod!
	c.c.conc.	clause		verb	advcl	Deși e supărat, a venit	verb	
10	c.c.cond.	R		verb	advmod		verb	
	c.c.cond.	N		verb	nmod	În cazul lui, o să admit.	verb	
	c.c.cond.	clause		verb	advcl	Dacă vrea, poate	verb	
11	c.c.cons.	R		verb	advmod		verb	
	c.c.cons.	N		verb	nmod	cu toate piedicile, a reușit	verb	
	c.c.cons.	clause		verb	advcl	L-a plouat, de e ud leoarcă	verb	
12	c.c.cumul.	R		verb	advmod		verb	
	c.c.cumul.	N		verb	nmod		verb	
	c.c.cumul.	clause		verb	advcl		verb	
13	c.c.cz.	R		verb	advmod		verb	
	c.c.cz.	N		verb	nmod	moare de foame	verb	
	c.c.cz.	clause		verb	advcl	a răcit că i-a fost frig	verb	
14	c.c.exc.	R		verb	advmod		verb	
	c.c.exc.	N		verb	nmod		verb	
	c.c.exc.	clause		verb	advcl		verb	
15	c.c.instr.	R		verb	advmod		verb	
	c.c.instr.	N		verb	nmod	merg cu mașina	verb	
	c.c.instr.	clause		verb	advcl	merg cu ce pot	verb	
16	c.c.l.	R		verb	advmod	acolo a plouat	verb	
	c.c.l.	N		verb	nmod	în Spania a plouat	verb	
	c.c.l.	clause		verb	advcl	te arunc unde nu tună	verb	
17	c.c.m.	R		verb	advmod	merg repede	verb	
	c.c.m.	N		verb	nmod	merg în salturi	verb	
	c.c.m.	clause		verb	advcl	merg cum pot	verb	
18	c.c.opoz.	R		verb	advmod		verb	
	c.c.opoz.	N		verb	nmod		verb	
	c.c.opoz.	clause		verb	advcl		verb	
19	c.c.rel.	R		verb	advmod		verb	
	c.c.rel.	N		verb	nmod		verb	
	c.c.rel.	clause		verb	advcl		verb	
20	c.c.scop.	R		verb	advmod		verb	
	c.c.scop.	N		verb	nmod	învăț pentru examen	verb	
	c.c.scop.	clause		verb	advcl	învăț ca să reușesc	verb	
21	c.c.soc.	R		verb	advmod		verb	
	c.c.soc.	N		verb	nmod	vorbesc cu prietenii	verb	
	c.c.soc.	clause		verb	advcl	vorbesc cu cine mă întreabă	verb	
22	c.c.t.	R		verb	advmod:tmod	a venit ieri	verb	
	c.c.t.	N		verb	nmod:tmod	a venit de dimineață	verb	
	c.c.t.	clause		verb	advcl:tmod	a venit când l-am chemat	verb	
23	c.d.	N sau P		verb	dobj	citesc cartea	verb	
	c.d.	clause		verb	ccomp	cred că e corect	verb	
	c.d.	P rep N		verb	dobj:expl	l-a chemat pe băiat	verb	
	c.d.	N cu prep+c.d.N fără prep		verb	iobj	îl învăț pe copil un joc	verb	urnează ca obiectul secundar un joc să fie dobj
	c.d.	Vmn		verbul a putea legat direct fără prep sau conj.	head pentru a putea, care devine aux	El nu poate suferi apa	Vmn	Vmn preia deprel, headul și dependențele lui putea (afară de neg, aux) iar putea se subordonează de Vmn ca aux
24	c.i.	N sau P		verb	iobj	citesc copilului	verb	
	c.i.	clause		verb	ccomp	spun cui ascultă		
	c.i.	clause		verb	ccomp	mă gândesc că e corect.	verb	de fapt, noi am adnotat așa c.prep cerut de regimul prepozițional al verbului, când era exprimat printr-o clause, dar și acela este o dependență obligatorie, nu facultativă.
	c.i.	P rep N		verb	iobj:expl	i-am spus băiatului	verb	
25	comp.	R		adj, adv	advmod	mai tare	adj, adv	gradele de comparație comp. Și superl. Ar trebui păstrate în al doilea strat
	comp.	R=ca		diverse	case 	tare ca piatra	subst	
	comp.	R=ca		verb	mark	scrie ca să fie citit	verb	
26	coord.	Punct			punct	mama, tata	prim coord	
	coord.	Cc			cc	tata și copilul	prim coord	
	coord.	altceva			conj	tata și copilul	prim coord	
27	corel.	Cc		un element de relație	cc	nici el	verb	probabil se va schimba și head-ul care la noi era de obicei un mijloc de relație. Trebuie readnotat manual
	corel.	neg		un element de relație	neg	nu numai	verb	
	corel.	R		un element de relație	advmod	atât de tare că	verb	
28	c.prep.			verb	iobj	se bucură de succes	verb	nu este o relație facultativă ci necesară
29	det.			subst	det		subst	la noi doar articol
30	el.pred.			verb	xcomp	merge veselă	verb	
31	incid.			verb	parataxis	fugi, zise ea	verb	
32	interj.			verb	discourse	o, nu cred!	verb	
33	narativ.			la noi nu era subordonat, era root	discourse	Și au plecat.	root	în UD aceste elemente sunt dependente de root, la UAIC ele erau head pentru primul verb regent
34	neg.			verb	neg		verb	
35	n.pred.	N, P, R etc.		vb. copulativ a fi	n.pred. preia dependențele subordonate la noi de VC, iar VC neadnotat înainte = cop			această adnotare dispare. n.pred devine root dacă VC era root, dacă apare într-o propoziție subordonată, va fi adnotat cu relația acesteia față de head-ul ei, care înainte stătea deasupra elementului de relație. În schimb, verbul copulativ subordonat de n.pred va primi relația cop
	n.pred.	clause		vb. copulativ a fi	dep	Problema e că el nu e atent.	headul de care era subordonat înainte VC, el urcă un nivel în arbore	cum nu avem notația n.pred, dacă este nevoie să îl adnotăm el fiind head, dar nu root, folosim adnotarea dep (dependență pe care convențiile sistemului nu ne permit să o precizăm)
	n.pred.	N, P, R etc.		alt vb. copulativ decât a fi	xcomp	el pare bolnav	alt vb. copulativ decât a fi	
	n.pred.	clause		alt vb. copulativ decât a fi	xcomp	A munci înseamnă să exersezi.	alt vb. copulativ decât a fi	structura headurilor nu se modifică față de UAICtb în cazul altor verbe copulative decât a fi
36	part.				mark	a munci		
37	prep.			N, P, M	case	sunt de acord		
	prep.			vb, adv	mark	de trimis, de mâine		
38	punct.			root	punct			dacă e vorba de punctul final, are head root. dacă nu, el trebuie sugordonat de headul subarborelui pe care îl izolează. Acesta nu va mai fi, ca la UAIC, un element de relație ci un cuvânt cu sens lexical.
39	refl.			verb	compound:reflex	mă pricep; se îngălbenește; se obișnuiește să...; mă rog		caz în care marchează caracterul intranzitiv al verbului și cere un determinant obligatoriu cu o anumită prepoziție
	refl.			verb	auxpass:reflex	legea se votează		trebuie adnotat de un expert, nu avem mărci în treebank pentru diateza pasivă formată cu reflexivul poate doar apariția unui c.ag subordonat de același head cu el
40	sbj.	cuvânt		verb	nsubj	Ion tace		
	sbj.	cuvânt		vb. pasiv	nsubjpass	Ion e chemat		
	sbj.	Vmn		verbul a putea legat direct fără prep sau conj.	head pentru a putea, care devine aux	Nu se poate face nimic	Vmn	Vmn preia deprel, headul și dependențele lui putea (afară de neg, aux) iar putea se subordonează de Vmn ca aux
	sbj.	clause		verb	csubj	Cine vrea poate		
	sbj.	clause		vb.pasiv	csubjpass	Ce era greu a fost făcut		
41	subord.			Cs=(că, să, ca ... să, căci, fiindcă, deoarece, încât, întrucât, dacă, deși)=mark	mark	Dacă se poate		
	subord.			Rw, Pw, Dw. Rw=unde, când, cum, cât, încotro	Pw=(+prep sau nu)cine, cui, ceea ce, cel ce, celui ce, celei ce, celor ce; Pw sau Dw=ce, care, cărui, cărei, căror, cât, câtă, câți, câte câtor 	Omul care a venit=nsubj; Nu știu despre ce vorbești=iobj; mă întreb ce este fericirea=dep (nume pred); a făcut ce a crezut =dobj; a ajuns unde a vrut=advmod etc.		această adnotare dispare fiind înlocuită cu relația clausei subordonate. dar în ce privește headul ei, care e un mijloc de relație, acesta va fi subordonat de headul propoziției subordonate. Dacă e o conjuncție subordonatoare, ea devine mark. dacă e un relativ, acesta trebuie adnotat manual cu relația lui în propoziția subordonată.
42	superl.	R		adj, adv	advmod	foarte stresante		
43	textual			root	discourse	I.1. Se aplică paragrafulanterior dacă...		în UD aceste elemente sunt dependente de root, la UAIC ele erau head pentru primul verb regent
44	voc.			verb	vocative	Mario, vino!		
	neadnotat			sunt stabilite relații de depemdență între componente	compound	patruzeci și trei		de adnotat manual; de folosit neapărat la numerale
	neadnotat				foreign			de adnotat manual
	neadnotat				goeswith			de adnotat manual
	neadnotat				list			de adnotat manual
	neadnotat			sunt stabilite relații de depemdență între componente	mwe	ca maimuțele să coboare din copac		de adnotat manual; de folosit la expresii, locuțiuni și la conjuncții compuse discontinue
	neadnotat				name			de adnotat manual
	neadnotat				reparandum			de adnotat manual
	neadnotat	NULL		negație, conjuncție element de punctuație	remnant	este cumine, nu obraznic; el nu e inginer ci profesor: Copilul - micăieri.		de adnotat manual
