@Library('libpipelines@master') _

hose {
    EMAIL = 'front'
    MODULE = 'egeo-ui-base'
    DEVTIMEOUT = 30
    RELEASETIMEOUT = 30
    REPOSITORY = 'egeo-ui-base'

    DEV = { config ->
        doUT(config)
        doDeploy(config)
        doPackage(config)
    }
}
