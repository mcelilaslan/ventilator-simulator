# Ventilator Asynchrony Simulator / MV Asenkroni Simülatörü

A live, sweeping mechanical-ventilator screen for teaching patient–ventilator asynchrony. Pick a scenario and the waveforms (pressure, flow, volume and the patient's muscle effort) start moving like on a real ICU ventilator. Ventilator settings and patient mechanics are adjustable, and every scenario has a one-click "fix" to compare before and after.

Hasta-ventilatör asenkronisini öğretmek için canlı akan bir mekanik ventilatör ekranı. Bir senaryo seçince basınç, akım, hacim ve hastanın kas eforu gerçek bir yoğun bakım ventilatöründeki gibi akmaya başlar. Ventilatör ayarları ve hasta mekaniği değiştirilebilir; her senaryoda öncesini ve sonrasını karşılaştırmak için tek tıkla "düzelt" seçeneği vardır.

**Live / Canlı:** https://mcelilaslan.github.io/ventilator-simulator/

## Features / Özellikler
- Modes: VC-CMV, PC-CMV, PRVC, PSV
- 14 scenarios: normal breathing, ineffective effort, delayed and auto-triggering, auto-PEEP with external PEEP, flow starvation, falling support in PRVC, double triggering, early and delayed cycling, reverse triggering, air trapping
- Adjustable patient: compliance, resistance, expiratory flow limitation, effort rate and strength, neural Ti, expiratory muscles, entrainment, cardiac oscillation; COPD and ARDS presets
- Inspiratory and expiratory hold maneuvers, event marks, saved presets, day and night themes
- Turkish and English; the language follows the browser and can be switched with the TR/EN button

## Run / Çalıştırma
Single self-contained `index.html`, no build step and no dependencies. Open it in a browser or serve it with GitHub Pages.

Tek dosyalık `index.html`; derleme ya da bağımlılık yok. Tarayıcıda açmanız ya da GitHub Pages ile yayınlamanız yeterli.

## Disclaimer / Uyarı
For education only, not for clinical decisions. The screen layout is inspired by ICU ventilators and is not any manufacturer's product.

Eğitim amaçlıdır, klinik karar için kullanılmaz. Ekran düzeni yoğun bakım ventilatörlerinden esinlenmiştir; herhangi bir üreticinin ürünü değildir.

## References / Kaynaklar
1. Murias G, Lucangelo U, Blanch L. Patient-ventilator asynchrony. *Curr Opin Crit Care* 2016;22:53–59.
2. Hamilton Medical. Patient-ventilator asynchrony reference card (ELO2019041N.04), 2023.
3. Tonetti T, Merola R, Gregoretti C, Ranieri VM. Patient–ventilator interaction. *Textbook of Critical Care*, Chapter 54, pp. 393–399.
4. Hess DR, Kacmarek RM. Patient-ventilator interaction. *Essentials of Mechanical Ventilation*, Chapter 15, pp. 153–166.
