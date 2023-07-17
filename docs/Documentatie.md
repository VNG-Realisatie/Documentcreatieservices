---
layout: page-with-side-nav
title: Documentatie Documentcreatie services
folder_files:
  - title: Bijlage C - Informatiemodel Documentcreatie v1 00 (20140402)
    path: documenten/Bijlage_C_-_Informatiemodel_Documentcreatie_v1_00_(20140402).pdf
    group: 110
    versie: 1.00
    status: Onbekend
    omschrijving: 
  - title: Documentcreatieservices 1.1 Schema's
    path: documenten/Documentcreatieservices_1.1.zip
    group: 110
    versie: 1.1
    status: 
    omschrijving: 
  - title: Releasenotes Documentcreatieservices v1.1
    path: documenten/Releasenotes-DCR-1.1.pdf
    group: 110
    versie: 1.1
    status: 
    omschrijving: 
  - title: Specificatie Documentcreatieservices v1.1
    path: documenten/Specificatie_Documentcreatieservices_v1.1.pdf
    group: 110
    versie: 1.1
    status: Definitief
    omschrijving: 
  - title: Testset Documentcreatie Services 1.1
    path: documenten/20141125-Testset_documentcreatie_1.1.zip
    group: 110
    versie: 1.1
    status: 
    omschrijving: 
  - title: Bijlage C - Informatiemodel Documentcreatie v1 00 (20140402)
    path: documenten/Bijlage_C_-_Informatiemodel_Documentcreatie_v1_00_(20140402).pdf
    path: documenten/Testset_Documentcreatie_Services_1.0.zip
    group: 100
    versie: 1.00
    status: Onbekend
    omschrijving: 
  - title: Documentcreatieservices v1.0.02 
    path: documenten/DCR_1_0_2.zip
    group: 100
    versie: 1.0.02
    status: Onbekend
    omschrijving: 
  - title: Specificatie Documentcreatieservices v1.01.02
    path: documenten/Specificatie_Documentcreatieservices_v1.01.02.pdf
    group: 100
    versie: 1.01.02
    status: Onbekend
    omschrijving: 
  - title: Testset Documentcreatie Services 1.0
    path: documenten/Testset_Documentcreatie_Services_1.0.zip
    group: 100
    versie: 1.0
    status: Onbekend
    omschrijving: 
---
# Documentatie Documentcreatie services

## Documentatie
* Koppelvlakspecificatie Documentcreatieservices 1.0.02 (inclusief bijlages)
* Schema's
* Compliancy testset Documentcreatie services 1.0
* Voorbeeldberichten

### Documentcreatieservices 1.1

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 110 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

### Documentcreatieservices 1.0

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 100 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>