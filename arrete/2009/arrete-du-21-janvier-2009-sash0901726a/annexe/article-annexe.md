# Article Annexe

<div align="center">

<table>
<tbody>
<tr>
<th>DONNÉES<br/>
</th>
<th colspan="2">VARIABLES<br/>
</th>
</tr>
<tr>
<td align="center">Tarifs des séjours GHS.<br/>
</td>
<td align="center">GHS<br/>
</td>
</tr>
<tr>
<td align="center">Forfait journalier FJ.<br/>
</td>
<td align="center">FJ<br/>
</td>
</tr>
<tr>
<td align="center">Durée de séjour DS.<br/>
</td>
<td align="center">DS<br/>
</td>
</tr>
<tr>
<td align="center">Taux de remboursement TR.<br/>
</td>
<td align="center">TR<br/>
</td>
</tr>
<tr>
<td align="center">Taux de ticket modérateur TM.<br/>
</td>
<td align="center">= 1 ― TR<br/>
</td>
</tr>
<tr>
<td align="center">Ticket modérateur forfaitaire 18 €.<br/>
</td>
<td align="center">18 €<br/>
</td>
</tr>
<tr>
<td align="center">Coefficient géographique CG.<br/>
</td>
<td align="center">CG<br/>
</td>
</tr>
<tr>
<td align="center">Coefficient de transition CT.<br/>
</td>
<td align="center">CT<br/>
</td>
</tr>
</tbody>
</table>

</div>

Modalités de détermination de la part payée par l'assurance maladie selon le cas

<div align="center">

<table>
<tbody>
<tr>
<th colspan="3">CAS DE PATIENT AVEC UN TICKET MODÉRATEUR À 20 %<br/>
</th>
</tr>
<tr>
<td align="center">Ticket modérateur M_TM.<br/>
</td>
<td align="center">M_TM = (GHS × CG × CT) × TM<br/>
</td>
</tr>
<tr>
<td align="center">Forfait journalier M_FJ.<br/>
</td>
<td align="center">M_FJ = (FJ × DS) + FJ (1)<br/>
</td>
</tr>
<tr>
<td align="center">Montant payé par l'assurance maladie AMO<br/>
</td>
</tr>
<tr>
<td align="center">Si M_TM ¸ M_FJ.<br/>
</td>
<td align="center">M_AMO = (GHS × CG × CT) × TR―(M_FJ-M_TM)<br/>
</td>
</tr>
<tr>
<td align="center">Si M_TM ¹ M_FJ.<br/>
</td>
<td align="center">M_AMO = (GHS × CG × CT × TR)<br/>
</td>
</tr>
</tbody>
</table>

</div>

<div align="center">

<table>
<tbody>
<tr>
<th colspan="3">CAS DE PATIENT EXONÉRÉ DU TM ET NON EXONÉRÉ DU FORFAIT JOURNALIER<br/>
</th>
</tr>
<tr>
<td align="center">Ticket modérateur M_TM.<br/>
</td>
<td align="center">0 <br/>
</td>
</tr>
<tr>
<td align="center">Forfait journalier M_FJ.<br/>
</td>
<td align="center">M_FJ = (FJ × DS) + FJ<br/>
</td>
</tr>
<tr>
<td align="center">Montant payé par l'assurance maladie AMO.<br/>
</td>
<td align="center">M_AMO = (GHS × CG × CT) ― ((FJ × DS) + FJ)<br/>
</td>
</tr>
</tbody>
</table>

</div>

<div align="center">

<table>
<tbody>
<tr>
<th colspan="3">CAS DE PATIENT EXONÉRÉ DU TM ET DU FORFAIT JOURNALIER<br/>
</th>
</tr>
<tr>
<td align="center">Ticket modérateur M_TM.<br/>
</td>
<td align="center">0<br/>
</td>
</tr>
<tr>
<td align="center">Forfait journalier M_FJ.<br/>
</td>
<td align="center">0<br/>
</td>
</tr>
<tr>
<td align="center">Montant payé par l'assurance maladie AMO.<br/>
</td>
<td align="center">M_AMO = GHS × CG × CT<br/>
</td>
</tr>
</tbody>
</table>

</div>

<div align="center">

<table>
<tbody>
<tr>
<th colspan="3">CAS DE PATIENT PRIS EN CHARGE À 100 %, SOUMIS AU TM DE 18 € ET NON EXONÉRÉ DU FORFAIT JOURNALIER<br/>
</th>
</tr>
<tr>
<td align="center">Ticket modérateur M_TM.<br/>
</td>
<td align="center">18 €<br/>
</td>
</tr>
<tr>
<td align="center">Forfait journalier M_FJ.<br/>
</td>
<td align="center">M_FJ = (FJ × DS) + FJ<br/>
</td>
</tr>
<tr>
<td align="center">Montant payé par l'assurance maladie AMO.<br/>
</td>
<td align="center">M_AMO = (GHS × CG × CT) ― ((FJ × DS) + FJ) ― 18<br/>
</td>
</tr>
</tbody>
</table>

</div>

<div align="center">

<table>
<tbody>
<tr>
<th colspan="3">CAS DE PATIENT PRIS EN CHARGE À 100 %, SOUMIS AU TM DE 18 € ET EXONÉRÉ DU FORFAIT JOURNALIER<br/>
</th>
</tr>
<tr>
<td align="center">Ticket modérateur M_TM.<br/>
</td>
<td align="center">18 €<br/>
</td>
</tr>
<tr>
<td align="center">Forfait journalier M_FJ.<br/>
</td>
<td align="center">0<br/>
</td>
</tr>
<tr>
<td align="center">Montant payé par l'assurance maladie AMO.<br/>
</td>
<td align="center">M_AMO = (GHS × CG × CT) ― 18<br/>
</td>
</tr>
</tbody>
</table>

</div>

(1) Le patient acquitte le forfait journalier le jour de sortie.
