---
layout: default
title: Deliverable 4.4 - Energy Performance Deliverable
---

## Deliverable 4.4 - Energy Performance Deliverable

Here is a dynamically generated table from a CSV file:

<table id="csv-table"></table>

<script>
    document.addEventListener('DOMContentLoaded', function() {
        renderCSVTable('{{ site.baseurl }}/tables/44-frameworks-energyPerformance.csv', 'csv-table');
    });
</script>
