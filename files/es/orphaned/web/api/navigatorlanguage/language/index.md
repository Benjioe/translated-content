---
title: NavigatorLanguage.language
slug: orphaned/Web/API/NavigatorLanguage/language
tags:
  - API
  - Gecko
  - Idioma
  - Lenguaje
  - NavigatorLanguage
  - Propiedad
  - Referencia
  - Referencia DOM de Gecko
  - Solo lectura
translation_of: Web/API/NavigatorLanguage/language
original_slug: Web/API/NavigatorLanguage/language
browser-compat: api.NavigatorLanguage.language
---
<div>{{APIRef("HTML DOM")}}</div>

<p>La propiedad de solo lectura <strong><code>NavigatorLanguage.language</code></strong> devuelve un string representando el lenguaje predefinido del usuario, generalmente es el lenguaje configurado para la interfaz del navegador.</p>

<h2 id="Sintaxis">Sintaxis</h2>

<pre class="syntaxbox">lang = globalObj.navigator.language
</pre>

<h3 id="Valores">Valores</h3>

<p><code>Un string que representa el código del lenguaje standard como se define en la</code> <a class="external" href="http://www.ietf.org/rfc/bcp/bcp47.txt">BCP 47</a>. Ejemplos de códigos válidos de lenguaje incluyen: "en", "en-US", "fr", "es-ES", etc.</p>

<h2 id="Ejemplo">Ejemplo</h2>

<pre class="brush: js">if (window.navigator.language != "en") {
  doLangSelect(window.navigator.language);
}
</pre>

<h2 id="Especificaciones">Especificaciones</h2>

{{Specifications}}

<h2 id="Compatibilidad_de_Navegadores">Compatibilidad de Navegadores</h2>

{{Compat}}

<h2 id="Ver_también">Ver también</h2>

<ul>
 <li>{{domxref("NavigatorLanguage.languages", "navigator.languages")}}</li>
 <li>{{domxref("navigator")}}</li>
</ul>