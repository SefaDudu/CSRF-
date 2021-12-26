 <h3> CSRF NEDİR ? </h3>
<hr />
<ul>
  <li> CSRF (Cross Site Request Forgery) genel yapı olarak sitenin açığından faydalanarak siteye sanki o kullanıcıymış gibi erişerek işlem yapmasını sağlar. Buna CSRF Zaafiyeti denir.
</li>
</ul>


 <h3>  CSRF ENGELLEMEK İÇİN YAPILABİLECEKLER ? </h3>
 
 
 
 <ul>
   <li> 
     CSRF Zafiyetleri genellikle post methodlarında yollanan verilerin kontrol edilmemesi sonucunda ortaya çıkmakta olduğu bilinmektedir.
	</li>
	<li>
		Genellikle sayfalarda kullanılan form elemanlarıyla yollanılan post verilerinin hangi sayfaya yollandığı bilinmekte. Bu bilgiler CSRF atakları yapmak için kullanılabilmektedir. Bu sayede dışarıdan gelen istek sahteliklerine karşı engel koymuş oluyoruz.
	</li>
  <li>  
    Çözüm olarak post methodlarına token işlemleri kullanılarak bu zaafiyetin önüne geçilmektedir.
  </li>
  <br>
  <img src="https://www.mshowto.org/images/articles/2019/06/062919_1952_MVCCSRFSald19.png" />
	 <br>
  <img src="https://www.mshowto.org/images/articles/2019/06/062919_1952_MVCCSRFSald20.png" />
  
 <br>
  <li>
    Bir başka zaafiyet şekli ise HTTP attribute kullanımının yanlışlığından kaynaklanmaktadır. Örneğin bir kullanıcı kaydında veriyi POST ile göndermek yerine GET ile yönlendirme işlemi yapıyorsak burada CSRf zaafiyeti için değişik senaryolar ortaya çıkmakta.
  </li>
  <br>
<p> Herhangi bir başka görüşe sahip iseniz <a href="https://www.linkedin.com/in/sefa-dudu-320a93205/">Buradan</a> benimle iletişime geçebilirsiniz.
