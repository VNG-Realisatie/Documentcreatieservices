---
layout: page-with-side-nav
title: Documentatie Documentcreatie services
folder_files:
  - title: Bijlage C - Informatiemodel Documentcreatie v1 00 (pdf)
    path: documenten/Bijlage_C_-_Informatiemodel_Documentcreatie_v1_00_(20140402).pdf
    group: 110
    versie: 1.00
    status: Onbekend
    omschrijving: 
    datum: 20140402
  - title: Documentcreatieservices 1.1 Schema's (zip)
    path: documenten/Documentcreatieservices_1.1.zip
    group: 110
    versie: 1.1
    status: 
    omschrijving: 
    datum: 20160622
  - title: Releasenotes Documentcreatieservices v1.1 (pdf)
    path: documenten/Releasenotes-DCR-1.1.pdf
    group: 110
    versie: 1.1
    status: 
    omschrijving: 
    datum: 20160622
  - title: Specificatie Documentcreatieservices v1.1 (pdf)
    path: documenten/Specificatie_Documentcreatieservices_v1.1.pdf
    group: 110
    versie: 1.1
    status: Definitief
    omschrijving: 
    datum: 20160622
  - title: Bijlage C - Informatiemodel Documentcreatie v1 00 (pdf)
    path: documenten/Bijlage_C_-_Informatiemodel_Documentcreatie_v1_00_(20140402).pdf
    path: documenten/Testset_Documentcreatie_Services_1.0.zip
    group: 100
    versie: 1.00
    status: Onbekend
    omschrijving: 
    datum: 20140406
  - title: Documentcreatieservices v1.0.02 (zip)
    path: documenten/DCR_1_0_2.zip
    group: 100
    versie: 1.0.02
    status: Onbekend
    omschrijving: 
    datum: 20150713
  - title: Specificatie Documentcreatieservices v1.01.02 (pdf)
    path: documenten/Specificatie_Documentcreatieservices_v1.01.02.pdf
    group: 100
    versie: 1.01.02
    status: Onbekend
    omschrijving: 
    datum: 20150713
  - title: Testset Documentcreatie Services 1.0 (zip)
    path: documenten/Testset_Documentcreatie_Services_1.0.zip
    group: 100
    versie: 1.0
    status: Onbekend
    omschrijving: 
    datum: 20140702
  - title: Testset Documentcreatie Services 1.1 (zip)
    path: documenten/20141125-Testset_documentcreatie_1.1.zip
    group: 100
    versie: 1.0
    status: 
    omschrijving: 
    datum: 20141125
---
# Documentatie Documentcreatie services

## Documentatie

### Documentcreatieservices 1.1

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
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
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

### Documentcreatieservices 1.0

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
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
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
