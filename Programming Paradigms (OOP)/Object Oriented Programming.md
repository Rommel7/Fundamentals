# Object Oriented Programming
   
## 1. Object
## 2. Class
Misal üçün bir ev üstündə misal göstərək. Fikiləşək ki bu evi tikmək üçün bizə nələr lazımdır. (Misal üçün: Çertyoj, avadanlıq, tikinti materialları və s.)
Çertyojda bizim evin dəqiq ölçüləri otaqların, mərtəbələrin sayı və s. göstərilir. Bu analogiyadan real həyatda bizə ev yaratmaq üçün çertyoj lazımdırsa onda obyekt yaratamaq üçün də bizə Class lazımdır.
Class özünə görə bir çertyojdur hansıda ki çox dəqiq və səlist obyekt izah olunub. Real həyatda bir çertyoj əsasında biz nə qədər istəsək ev yarada bilərik.
Bizə ancaq tikinti materiallarının qıtlığı maneə ola bilər. Proqramlaşdırmada da hər şey bu yolnan işləyir. Bir classdan nə qədər istəsən obyekt düzəltmək olar.
Bu obyektlər bir-birindən ancaq adları ilə fərqlənəcək. Tikinti maserialı isə kompüterin istifadə elədiyi CPU və RAM resurslardır.
Obyekti ən sadə olaraq anlatmağa çalışsaq ona koddaki sadə bir dəyişən kimi baxmaq olar. Yaratdığınız bu obyektnən onun classında proqramlaşdırdığınıza uyğun olaraq nə istəsəz edə bilərsiz.
Məsələn classda hər hansı bir metod və ya fəaliyyət yazmışdınızsa siz onlara obyektə müraciət edərək çağıra bilərsiniz.
Nəticələr:
Class və obyektin anlamına başa düşmək OOP-nin 80%ni başa düşməkə bərabərdir.
Class - çertyojdur hansının ki əsasında obyekt yaradılır.
Object - ən sadə bir dəyişəndir.
Bir classdan - xeyli sayda obyektlər yaratmaq olar.
Classların adı böyük hərifənən, obyektlərin adı isə kiçik hərifənən yazılır.

## 3. Inheritance
Inheritance (Nəsil salmaq) olan class əsasında daha spesefik bir class yaratmaqdır. Lakin onların daxili eyni olmamalıdır yəni copy olmamalıdır.
Buda Inheritance-in əsas məqsədini izah edir. Tutaq ki bir insanı izah edən class var. (Onun dəyişənləri - saç rəngi, boyu, çəkisi və s. Onun fəaliyyəti - gəzmək, yatmaq, yemək.)
İndi istə bir sürücü classı yaradaq bunun əsasında. Bir class yaradırıq və onun adını sürücü qoyub, insan classının Inheritance-i kimi qeyd edirik.
Ona sürmək metodu əlavə edirik və digər insan dəyişənlərini və fəaliyyətini artırmağa ehtiyac qalmır. Təbiidir ki bir superclassdan biz bir neçə alt class da yarada bilərik, məsələn proqramist və ya hərbçi.
Sürücü altclassından da daha bir alt class yük və ya maşın sürücü classıda yarada bilərik.
Inheritance demək olar ki hər yerdə tədbiq eləmək olar- kodun sayını azaltmaq üçün. 

## 4. Polymorphism

## 5. Abstraction

## 6. Encapsulation
İnkapsulyasiya - etimoloji olaraq hər hansısa bir şeyin kapsulaya yerləşdirilməsi, onun qorunması deməkdir. Bizim üçün isə bu class olacaq (onun metod və dəyişənləri).
Misal göstərək: Tutaq ki sizin bir avtomobiliniz var. O avtomobilin mexanizmini 2 əsas hissəyə bölmək olar. 
1-ci maşını idarə etmək üçün olan mexanizm. 2-ci digər bütün mexanizmlər. Avtomobilin için idarəetmə üçün olan mexaniz əsas 4 hissədən ibarətdir (Rul, pedal, sürət ötürücü, və spidometr).
Digər mexanizmlər isə tutaq mühərrikin içindəkilər bundan dəfələrlə çoxdu. Sürücüyə onu idarə etmək üçün 1-ci hissəni bilmək kifayət edir. Ona digər hissələri bilmək lazım deyil. O hətta onların olmasını da təxmin etməyə bilər.