# DNS nədir, və o necə işləyir.
Kompüter vebdə ada sahib deyil, data mübadiləsi IP-adreslər üzərindən həyata keçirilir.
IP-adreslər(Internet Protocol Address) — veb internetdə nömrələnmiş adresdir, misal olaraq: 123.123.123.123. 
Belə IP-adresləri insanın yadda saxlaması çətin bir işdir. Gündəlik olaraq 10larca sayta daxil olursuzsa bu 10 dəfə də çətinləşir.
Bu telefon nömrələrini yadda saxlamaqa bənzəyir, buna analoq olaraq siz IP-adresləri telefon kitabçasından istifadə edərək nömrələri yadda saxlaya bilərsiz.
İnternetdə telefon kitabçası rolunu DNS (Domain Name System), domen adnlar sistemii yerinə yetirir.
İnternet-brauzerində hər hansı bir sayt adı daxil etdikdə o serverə ulaşmaq üçün özünün IP-adres qarşılığını tapır.  

# DNS server nədir?

## «DNS-server» — «proqramdır», hansı ki özündə IP-adresləri domen adına uyğun olaraq saxlayır, misal olaraq belə:

		Domen			Serverin IP-adresi
		reg.az			194.58.116.30

Когда вы регистрируете новый домен, ни один DNS-сервер в Интернет о нём не знает. 
И пока на DNS-серверах Интернета не появится информация о вашем домене, ни сайт, ни почта, никакие другие сервисы работать не будут.
Чтобы DNS-серверы в Интернет узнали о вашем домене, им это должен кто-то рассказать, и этот кто-то — DNS-сервер, который вы прописываете для своего домена. 
Он играет роль «глашатая», который всегда хранит самую свежую информацию о вашем домене. 
Например, DNS-серверы хостинга ns1.hosting.reg.az и ns2.hosting.reg.az хранят информацию о доменах, которые подключены к хостингу REG.AZ.
DNS-серверы прописываются парами, это делается для лучшей отказоустойчивости: если один DNS-сервер выйдет из строя, другой останется работать.