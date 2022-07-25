[Use the Dataform CLI](https://docs.dataform.co/dataform-cli)

    npm i -g @dataform/cli
    dataform init postgres spike-dataform
    cd spike-dataform
    dataform init-creds postgres
    echo "config { type: 'view' } SELECT 1 AS test" > definitions/example.sqlx
    dataform run
