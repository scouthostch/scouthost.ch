---
layout: page
title: Kontakt
permalink: /request/
---

<h2>Kontaktiere uns</h2>

<p>Das hier beschirebene Angebot interessiert dich? </p>
<p>Du hat Fragen welche auf der Seite noch nicht beantwortet wurden?</p>
<p>Oder du willst infach nur mit jemandem Kontakt haben :)</p>
<br />
<hr />
<br />
<p>Melde dich mit Hilfe von diesem Kontaktformular:</p>

<form action="https://docs.google.com/forms/d/19dFnLboLB3v-exCOCJGwQUkt3Cjr6T_51y1AXnN_U-U/formResponse">
    <label for="request-type">Anfragetyp</label>
    <select name="entry.219969242">
		<option selected disabled>Anfragetyp wählen</option>
		<option>Allgemeine Anfrage</option>
		<option>Technische Frage</option>
		<option>Bestellung</option>
		<option>Support</option>
	</select>
    <br />
    <label for="name" class="bold">Vor- / Nachname</label>
    <input name="entry.1595707891" type="text" id="name" required />
    <br />
    <!-- SINGLE LINE TEXT FIELD -->
    <label for="mail" class="bold">E-Mail-Adresse</label>
    <input name="emailAddress" type="email" id="mail" required />
    <br />
    <!-- MULTI-LINE TEXT FIELD -->
    <label for="question" class="bold">Frage</label>
    <textarea name="entry.1968007443" id="request"></textarea>
    <!-- SUBMIT BUTTON -->
    <input class="button" type="submit" value="Senden">
</form>
