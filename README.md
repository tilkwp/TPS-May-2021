# TPS-May-2021
____
Tabular Playground Series - May 2021
Набор данных, используемый для этого соревнования, является синтетическим, но основан на реальном наборе данных и сгенерирован с использованием CTGAN. Исходный набор данных предназначен для прогнозирования категории продукта электронной коммерции с учетом различных атрибутов листинга. Хотя функции анонимны, у них есть свойства, относящиеся к реальным функциям.
____

В данном соревнованиии решается задача мультиклассовой классификации. В качестве метрики рассматриваются функция логистических потерь

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mtext>log loss</mtext>
  <mo>=</mo>
  <mo>&#x2212;<!-- − --></mo>
  <mfrac>
    <mn>1</mn>
    <mi>N</mi>
  </mfrac>
  <munderover>
    <mo>&#x2211;<!-- ∑ --></mo>
    <mrow class="MJX-TeXAtom-ORD">
      <mi>i</mi>
      <mo>=</mo>
      <mn>1</mn>
    </mrow>
    <mi>N</mi>
  </munderover>
  <munderover>
    <mo>&#x2211;<!-- ∑ --></mo>
    <mrow class="MJX-TeXAtom-ORD">
      <mi>j</mi>
      <mo>=</mo>
      <mn>1</mn>
    </mrow>
    <mi>M</mi>
  </munderover>
  <msub>
    <mi>y</mi>
    <mrow class="MJX-TeXAtom-ORD">
      <mi>i</mi>
      <mi>j</mi>
    </mrow>
  </msub>
  <mi>log</mi>
  <mo>&#x2061;<!-- ⁡ --></mo>
  <mo stretchy="false">(</mo>
  <msub>
    <mi>p</mi>
    <mrow class="MJX-TeXAtom-ORD">
      <mi>i</mi>
      <mi>j</mi>
    </mrow>
  </msub>
  <mo stretchy="false">)</mo>
  <mo>,</mo>
</math>
