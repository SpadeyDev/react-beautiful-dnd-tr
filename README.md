## ⚠️ Bakım & Destek

Bu kütüphane Atlassian ürünleri tarafından yoğun bir şekilde kullanılmaya devam ediyor, ancak şu anda diğer önceliklere odaklanmış durumdayız ve daha fazla özellik geliştirme veya iyileştirme için mevcut bir planımız yok.

Burada GitHub'da olmaya devam edecek ve gerektiğinde kritik güncellemeleri (örn. varsa güvenlik düzeltmeleri) yapmaya devam edeceğiz, ancak sorunları ve çekme isteklerini aktif olarak izlemeyecek veya yanıtlamayacağız.

Bir sonraki duyuruya kadar incelenmeyecekleri veya işleme alınmayacakları için sorun veya çekme isteği oluşturmamanızı öneririz.

> [!Önemli]
>
> **Güncelleme: 3 Nisan 2024**
>
> <a href="https://www.youtube.com/watch?v=uySl2yiUYE4"><img src="https://github.com/alexreardon/files/assets/2182637/bb7740a3-875c-49aa-be54-e7268d836d60" width="300px" /></a>
>
> [📺 Youtube'da izle](https://www.youtube.com/watch?v=uySl2yiUYE4) <br> [🗣️ Tartışma](https://github.com/atlassian/react-beautiful-dnd/issues/2573)

<br>

---

<p align="center">
  <img src="https://user-images.githubusercontent.com/2182637/53611918-54c1ff80-3c24-11e9-9917-66ac3cef513d.png" alt="react beautiful dnd logo" />
</p>
<h1 align="center">react-beautiful-dnd <small><sup>(rbd)</sup></small></h1>

<div align="center">

**Harika** ve **erişilebilir** listeler için sürükle ve bırak [`React`](https://facebook.github.io/react/)

[![CircleCI branch](https://img.shields.io/circleci/project/github/atlassian/react-beautiful-dnd/master.svg)](https://circleci.com/gh/atlassian/react-beautiful-dnd/tree/master)
[![npm](https://img.shields.io/npm/v/react-beautiful-dnd.svg)](https://www.npmjs.com/package/react-beautiful-dnd)

![quote application example](https://user-images.githubusercontent.com/2182637/53614150-efbed780-3c2c-11e9-9204-a5d2e746faca.gif)

[İstersen örnek ile test edebilirsin.](https://react-beautiful-dnd.netlify.com/iframe.html?selectedKind=board&selectedStory=simple)

</div>

## Temel Özellikler

- Öğelerin harika ve [doğal hareketi](/docs/about/animations.md)
- [Erişilebilir](/docs/about/accessibility.md): güçlü klavye ve ekran okuyucu desteği ♿️
- [Son derece performanslı](/docs/support/media.md) 🚀
- Başlaması kolay, temiz ve güçlü api
- Standart tarayıcı etkileşimleriyle son derece iyi çalışır
- [Düzenli tasarım](/docs/guides/preset-styles.md)
- Ek sarmalayıcı dom düğümleri oluşturmaya gerek yok - flexbox ve odak yönetimi dostu!

## Hemen Başla 👩‍🏫

react-beautiful-dnd `kullanmaya mümkün olduğunca çabuk başlamanıza yardımcı olmak için `[egghead.io 🥚](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd) adresinde ücretsiz bir kurs oluşturduk.

[![course-logo](https://user-images.githubusercontent.com/2182637/43372837-8c72d3f8-93e8-11e8-9d92-a82adde7718f.png)](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd)

## Şu anda desteklenen özellikler ✅

- Dikey listeler ↕
- Yatay listeler ↔
- Listeler arasında hareket (▤ ↔ ▤)
- [Sanal liste desteği 👾](/docs/patterns/virtual-lists.md) - 60 fps'de 10.000 öğenin kilidini açma
- [Öğeleri birleştirme](/docs/guides/combining.md)
- Fare 🐭, klavye 🎹♿️ ve dokunmatik 👉📱 (mobil, tablet vb.) desteği
- [Çoklu sürükleme desteği](/docs/patterns/multi-drag.md)
- İnanılmaz ekran okuyucu desteği ♿️ - İngilizce ekran okuyucular için kutudan çıkar çıkmaz harika bir deneyim sağlıyoruz 📦. Ayrıca ihtiyaç duyanlar için tam özelleştirme kontrolü ve uluslararasılaştırma desteği sağlıyoruz 💖
- Koşullu sürükleme](/docs/api/draggable.md#optional-props) ve [koşullu bırakma](/docs/api/droppable.md#conditionally-dropping)
- Tek sayfada birden fazla bağımsız liste
- Esnek öğe boyutları - sürüklenebilir öğeler farklı yüksekliklere (dikey listeler) veya genişliklere (yatay listeler) sahip olabilir
- [Sürükleme sırasında öğe ekleme ve kaldırma](/docs/guides/changes-while-dragging.md)
- Anlamsal `<tablo>` yeniden sıralaması ile uyumlu - [tablo kalıbı](/docs/patterns/tables.md)
- Otomatik kaydırma](/docs/guides/auto-scrolling.md) - sürükleme sırasında konteynerleri ve pencereyi gerektiği gibi otomatik olarak kaydırır (klavye ile bile 🔥)
- Özel sürükleme tutamaçları - bir öğenin tamamını sadece bir kısmından sürükleyebilirsiniz
- Sürükleme sırasında sürüklenen öğeyi başka bir öğeye taşıyabilme (klon, portal) - [Reparenting your `<Draggable />`](/docs/guides/reparenting.md)
- [Reparenting your `<Draggable />`](/docs/guides/reparenting.md)
- [Komut dosyası sürükle ve bırak deneyimleri oluşturun 🎮](/docs/sensors/sensor-api.md)
- Uzantıların [istediğiniz herhangi bir girdi türünü 🕹] desteklemesine izin verir (/docs/sensors/sensor-api.md)
- 🌲 [`@atlaskit/tree`](https://atlaskit.atlassian.com/packages/confluence/tree) paketi aracılığıyla ağaç desteği
- Bir `<Droppable />` listesi bir kaydırma konteyneri olabilir (kaydırılabilir bir ebeveyni olmadan) veya bir kaydırma konteynerinin çocuğu olabilir (aynı zamanda kaydırılabilir bir ebeveyni olmayan)
- Bağımsız iç içe listeler - bir liste başka bir listenin alt listesi olabilir, ancak öğeleri üst listeden alt listeye sürükleyemezsiniz
- Sunucu tarafı oluşturma (SSR) uyumlu - bkz [resetServerContext()](/docs/api/reset-server-context.md)
- Varsayılan olarak [iç içe etkileşimli öğeler](/docs/api/draggable.md#interactive-child-elements-within-a-draggable-) ile iyi çalışır.

## Motivasyon 🤔

`react-beautiful-dnd` herkesin kullanabileceği listeler için güzel sürükle ve bırak oluşturmak için var - göremeyen insanlar bile. Projenin geçmişi ve motivasyonları hakkında iyi bir genel bakış için bu harici kaynaklara göz atabilirsiniz:

- 📖 [Sürükle ve bırak yöntemini yeniden düşünmek](https://medium.com/@alexandereardon/rethinking-drag-and-drop-d9f5770b4e6b)
- 🎧 [React podcast: hızlı, erişilebilir ve güzel sürükle ve bırak](https://reactpodcast.simplecast.fm/17)

## Herkes için not ✌️

React içinde sürükle ve bırak etkileşimlerine izin veren birçok kütüphane var. Bunlardan en dikkate değer olanı muhteşem [`react-dnd`](https://github.com/react-dnd/react-dnd). Özellikle [wildly inconsistent](https://www.quirksmode.org/blog/archives/2009/09/the_html5_drag.html) html5 sürükle ve bırak özelliği ile iyi çalışan harika bir sürükle ve bırak ilkelleri seti sağlamada inanılmaz bir iş çıkarır. `react-beautiful-dnd` özellikle listeler (dikey, yatay, listeler arası hareket, iç içe listeler vb.) için oluşturulmuş daha üst düzey bir soyutlamadır. Bu işlevsellik alt kümesi içinde `react-beautiful-dnd` güçlü, doğal ve güzel bir sürükle ve bırak deneyimi sunar. Bununla birlikte, `react-dnd` tarafından sunulan işlevselliğin genişliğini sağlamaz. Bu nedenle `react-beautiful-dnd` kullanım durumunuza bağlı olarak size uygun olmayabilir.

## Dokümantasyon 📖

### Hakkında 👋

- [Kurulum](/docs/about/installation.md)
- [Örnekler ve numuneler](/docs/about/examples.md)
- [Başlayın](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd)
- [Tasarım ilkeleri](/docs/about/design-principles.md)
- [Animasyonlar](/docs/about/animations.md)
- [Erişilebilirlik](/docs/about/accessibility.md)
- [Tarayıcı desteği](/docs/about/browser-support.md)

### Sensörler 🔉

> Bir kişinin bir sürüklenmeyi başlatma ve kontrol etme yolları

- [Fare ile sürükleme 🐭](/docs/sensors/mouse.md)
- [Dokunmatik sürükleme 👉📱](/docs/sensors/touch.md)
- [Klavye ile sürükleme 🎹♿️](/docs/sensors/keyboard.md)
- [Kendi sürüklemenizi oluşturun](/docs/sensors/sensor-api.md) (herhangi bir girdi türünün yanı sıra komut dosyası deneyimlerine de izin verir)

### API 🏋️‍

![diagram](https://user-images.githubusercontent.com/2182637/53607406-c8f3a780-3c12-11e9-979c-7f3b5bd1bfbd.gif)

- [`<DragDropContext />`](/docs/api/drag-drop-context.md) - _Uygulamanızın sürükle ve bırak özelliğinin etkin olmasını istediğiniz bölümünü sarar_
- [`<Droppable />`](/docs/api/droppable.md) - _İçine düşülebilen bir alan. <Draggable />`s_ içerir
- [`<Draggable />`](/docs/api/draggable.md) - _Neler sürüklenebilir_
- [`resetServerContext()`](/docs/api/reset-server-context.md) - _Sunucu tarafı işleme (SSR)_ için yardımcı program

### Kılavuzlar 🗺

- [`<DragDropContext />` yanıtlayıcıları](/docs/guides/responders.md) - _`onDragStart`, `onDragUpdate`, `onDragEnd` ve `onBeforeDragStart`_
- [Combining `<Draggable />`s](/docs/guides/combining.md)
- [Ortak kurulum sorunları](/docs/guides/common-setup-issues.md)
- [Using `innerRef`](/docs/guides/using-inner-ref.md)
- [Kurulum sorunu algılama ve hata kurtarma](/docs/guides/setup-problem-detection-and-error-recovery.md)
- [DağılabilirId` ve `droppableId`ler için kurallar](/docs/guides/identifiers.md)
- [Tarayıcı odağının korunması](/docs/guides/browser-focus.md)
- [Düşme animasyonunu özelleştirme veya atlama](/docs/guides/drop-animation.md)
- [Otomatik kaydırma](/docs/guides/auto-scrolling.md)
- [Ekran okuyucuyu kontrol etme](/docs/guides/screen-reader.md)
- [Html5 `doctype` kullanın](/docs/guides/doctype.md)
- [`TypeScript` ve `flow`: tür bilgisi](/docs/guides/types.md)
- [<svg>`leri sürükleme](/docs/guides/dragging-svgs.md)
- [Görüntü titremesini önleme](/docs/guides/avoiding-image-flickering.md)
- [Görünür olmayan ön ayar stilleri](/docs/guides/preset-styles.md)
- [Kaydırma kaplarını nasıl tespit ediyoruz](/docs/guides/how-we-detect-scroll-containers.md)
- [Dom olaylarını nasıl kullanıyoruz](/docs/guides/how-we-use-dom-events.md) - _react-beautiful-dnd`_ üzerine inşa etmeniz gerekiyorsa kullanışlıdır
- [Sürükleme sırasında `<Draggable />` ekleme (11.x davranışı)](/docs/guides/changes-while-dragging.md) - _⚠️ Advanced_
- [İçerik Güvenliği Politikası Oluşturma](/docs/guides/content-security-policy.md)

### Desenler 👷‍

- [Sanal listeler 👾](/docs/patterns/virtual-lists.md)
- [Çoklu sürükleme](/docs/patterns/multi-drag.md)
- [Tablolar](/docs/patterns/tables.md)
- [Reparenting a `<Draggable />`](/docs/guides/reparenting.md) - _Using our cloning API or your own portal_

### Destek 👩‍⚕️

- [Mühendislik sağlığı](/docs/support/engineering-health.md)
- Topluluk ve eklentiler](/docs/support/community-and-addons.md)
- [Sürüm notları ve değişiklik günlüğü](https://github.com/atlassian/react-beautiful-dnd/releases)
- [Yükseltme](/docs/support/upgrading.md)
- [Yol haritası](https://github.com/atlassian/react-beautiful-dnd/issues)
- [Medya](/docs/support/media.md)

## Bunu diğer dillerde okuyun 🌎

- [![kr](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/South-Korea.png) **한글/Korean**](https://github.com/LeeHyungGeun/react-beautiful-dnd-kr)
- [![ru](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Russia.png) **На русском/Russian**](https://github.com/vtereshyn/react-beautiful-dnd-ru)
- [![pt](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Brazil.png) **Português/Portuguese**](https://github.com/dudestein/react-beautiful-dnd-pt)
- [![gr](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Greece.png) **Ελληνικά/Greek**](https://github.com/milvard/react-beautiful-dnd-gr)
- [![ja](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Japan.png) **日本語/Japanese**](https://github.com/eltociear/react-beautiful-dnd-ja)
- [![tr](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Turkey.png) **Türkçe/Turkiye**](https://github.com/chefberke/react-beautiful-dnd-tr)


## Kurucusu ✍️

Alex Reardon [@alexandereardon](https://twitter.com/alexandereardon)

> Alex artık bu projenin kişisel bakımını yapmıyor. Diğer harika bakımcılar bu projeyi ileriye taşıyor.

## Bakımcılar

- [Daniel Del Core](https://twitter.com/danieldelcore)
- Diğer birçok [@Atlassian](https://twitter.com/Atlassian)'lar!

## İşbirlikçiler 🤝

- Bogdan Chadkin [@IAmTrySound](https://twitter.com/IAmTrySound)
