limited_portal = configure_file(input: 'limited.portal.in',
    output: 'limited.portal',
    configuration: test_portal_conf,
    install: enable_installed_tests,
    install_dir: installed_tests_dir / 'portals/limited',
)

configure_file(input: 'limited-portals.conf',
    output: '@PLAINNAME@',
    copy: true,
    install: enable_installed_tests,
    install_dir: installed_tests_dir / 'portals/limited',
)
