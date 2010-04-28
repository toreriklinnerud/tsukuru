Tsukuru will fetch your latest bundle and prepare it for running locally. It keeps an archive of downloaded bundles. You can also use restore from a local bundle (archived or manually downloaded).

    Usage: reanimate
        -a, --app NAME                   Application name
        -c, --capture                    Capture a new bundle instead of using the latest one
        -p, --password                   Yuur Heroku password
        -h, --help                       Display this message
        -l, --local FILE                 Use a local bundle instead of downloading
        -t, --target PATH                Path to where the application should be restored
        -r, --reindex                    Start search deamon and reindex (sunspot + solr only)
        -u, --username                   Your Heroku username
