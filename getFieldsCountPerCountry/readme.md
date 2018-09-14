This piece of code is used to calculate number of fields in each country.

It uses three data sources: fields, countries, and growers. Here we assume that the first grower in a field's "associations.agrian.grower" array is the representing grower. Then the grower's "address.country_id" links back to country.

The output is a table that summarizes number of fields per country