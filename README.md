# urbancode-cp4mcm
Reuseable deployment yamls for UrbanCode Deploy and CP4MCM

## Run Command
`
oc process -f deployable.yaml -p APP_NAME=myapp -p NAMESPACE=default | oc apply -f -
`
