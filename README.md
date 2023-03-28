# soda-core-actions

      uses: carlosnizolli/soda-core-actions:month
      env:
        POSTGRES_USERNAME: ${{ secrets.POSTGRES_USERNAME }}
        POSTGRES_PASSWORD: ${{ secrets.POSTGRES_PASSWORD }}
        API_PUBLIC: ${{ secrets.SODA_API_PUBLIC }}
        API_PRIVATE: ${{ secrets.SODA_API_PRIVATE }}
      with:
         data_source: datasource_name
         configuration: /configuration.yml
         checks:/ checks.yml
         month: Dezembro
         date1: 2022-12-01
         date2: 2023-01-01
