
INSTALL(FILES
  generated/doc/couchbase-cli/couchbase-cli-analytics-link-setup.html
  generated/doc/couchbase-cli/couchbase-cli-bucket-compact.html
  generated/doc/couchbase-cli/couchbase-cli-bucket-create.html
  generated/doc/couchbase-cli/couchbase-cli-bucket-delete.html
  generated/doc/couchbase-cli/couchbase-cli-bucket-edit.html
  generated/doc/couchbase-cli/couchbase-cli-bucket-flush.html
  generated/doc/couchbase-cli/couchbase-cli-bucket-list.html
  generated/doc/couchbase-cli/couchbase-cli-cluster-edit.html
  generated/doc/couchbase-cli/couchbase-cli-node-to-node-encryption.html
  generated/doc/couchbase-cli/couchbase-cli-cluster-init.html
  generated/doc/couchbase-cli/couchbase-cli-ip-family.html
  generated/doc/couchbase-cli/couchbase-cli-collect-logs-start.html
  generated/doc/couchbase-cli/couchbase-cli-collect-logs-status.html
  generated/doc/couchbase-cli/couchbase-cli-collect-logs-stop.html
  generated/doc/couchbase-cli/couchbase-cli-collection-manage.html
  generated/doc/couchbase-cli/couchbase-cli-eventing-function-setup.html
  generated/doc/couchbase-cli/couchbase-cli-failover.html
  generated/doc/couchbase-cli/couchbase-cli-group-manage.html
  generated/doc/couchbase-cli/couchbase-cli-help.html
  generated/doc/couchbase-cli/couchbase-cli-host-list.html
  generated/doc/couchbase-cli/couchbase-cli-master-password.html
  generated/doc/couchbase-cli/couchbase-cli-node-init.html
  generated/doc/couchbase-cli/couchbase-cli-rebalance-status.html
  generated/doc/couchbase-cli/couchbase-cli-rebalance-stop.html
  generated/doc/couchbase-cli/couchbase-cli-rebalance.html
  generated/doc/couchbase-cli/couchbase-cli-recovery.html
  generated/doc/couchbase-cli/couchbase-cli-reset-admin-password.html
  generated/doc/couchbase-cli/couchbase-cli-reset-cipher-suites.html
  generated/doc/couchbase-cli/couchbase-cli-server-add.html
  generated/doc/couchbase-cli/couchbase-cli-server-eshell.html
  generated/doc/couchbase-cli/couchbase-cli-server-info.html
  generated/doc/couchbase-cli/couchbase-cli-server-list.html
  generated/doc/couchbase-cli/couchbase-cli-server-readd.html
  generated/doc/couchbase-cli/couchbase-cli-setting-alert.html
  generated/doc/couchbase-cli/couchbase-cli-setting-audit.html
  generated/doc/couchbase-cli/couchbase-cli-setting-autofailover.html
  generated/doc/couchbase-cli/couchbase-cli-setting-autoreprovision.html
  generated/doc/couchbase-cli/couchbase-cli-setting-alternate-address.html
  generated/doc/couchbase-cli/couchbase-cli-setting-cluster.html
  generated/doc/couchbase-cli/couchbase-cli-setting-compaction.html
  generated/doc/couchbase-cli/couchbase-cli-setting-index.html
  generated/doc/couchbase-cli/couchbase-cli-setting-ldap.html
  generated/doc/couchbase-cli/couchbase-cli-setting-query.html
  generated/doc/couchbase-cli/couchbase-cli-setting-saslauthd.html
  generated/doc/couchbase-cli/couchbase-cli-setting-notification.html
  generated/doc/couchbase-cli/couchbase-cli-setting-password-policy.html
  generated/doc/couchbase-cli/couchbase-cli-setting-rebalance.html
  generated/doc/couchbase-cli/couchbase-cli-setting-security.html
  generated/doc/couchbase-cli/couchbase-cli-setting-xdcr.html
  generated/doc/couchbase-cli/couchbase-cli-ssl-manage.html
  generated/doc/couchbase-cli/couchbase-cli-user-change-password.html
  generated/doc/couchbase-cli/couchbase-cli-user-manage.html
  generated/doc/couchbase-cli/couchbase-cli-xdcr-replicate.html
  generated/doc/couchbase-cli/couchbase-cli-xdcr-setup.html
  generated/doc/couchbase-cli/couchbase-cli.html
  DESTINATION share/doc/couchbase-cli)

INSTALL(FILES
  generated/doc/cblogredaction/cblogredaction.html
  DESTINATION share/doc/cblogredaction)

IF (NOT WIN32)
  INSTALL(FILES
    generated/man/man1/couchbase-cli-analytics-link-setup.1
    generated/man/man1/couchbase-cli-bucket-compact.1
    generated/man/man1/couchbase-cli-bucket-create.1
    generated/man/man1/couchbase-cli-bucket-delete.1
    generated/man/man1/couchbase-cli-bucket-edit.1
    generated/man/man1/couchbase-cli-bucket-flush.1
    generated/man/man1/couchbase-cli-bucket-list.1
    generated/man/man1/couchbase-cli-cluster-edit.1
    generated/man/man1/couchbase-cli-node-to-node-encryption.1
    generated/man/man1/couchbase-cli-cluster-init.1
    generated/man/man1/couchbase-cli-ip-family.1
    generated/man/man1/couchbase-cli-collect-logs-start.1
    generated/man/man1/couchbase-cli-collect-logs-status.1
    generated/man/man1/couchbase-cli-collect-logs-stop.1
    generated/man/man1/couchbase-cli-collection-manage.1
    generated/man/man1/couchbase-cli-eventing-function-setup.1
    generated/man/man1/couchbase-cli-failover.1
    generated/man/man1/couchbase-cli-group-manage.1
    generated/man/man1/couchbase-cli-help.1
    generated/man/man1/couchbase-cli-host-list.1
    generated/man/man1/couchbase-cli-master-password.1
    generated/man/man1/couchbase-cli-node-init.1
    generated/man/man1/couchbase-cli-rebalance-status.1
    generated/man/man1/couchbase-cli-rebalance-stop.1
    generated/man/man1/couchbase-cli-rebalance.1
    generated/man/man1/couchbase-cli-recovery.1
    generated/man/man1/couchbase-cli-reset-admin-password.1
    generated/man/man1/couchbase-cli-reset-cipher-suites.1
    generated/man/man1/couchbase-cli-server-add.1
    generated/man/man1/couchbase-cli-server-eshell.1
    generated/man/man1/couchbase-cli-server-info.1
    generated/man/man1/couchbase-cli-server-list.1
    generated/man/man1/couchbase-cli-server-readd.1
    generated/man/man1/couchbase-cli-setting-alert.1
    generated/man/man1/couchbase-cli-setting-audit.1
    generated/man/man1/couchbase-cli-setting-autofailover.1
    generated/man/man1/couchbase-cli-setting-autoreprovision.1
    generated/man/man1/couchbase-cli-setting-alternate-address.1
    generated/man/man1/couchbase-cli-setting-cluster.1
    generated/man/man1/couchbase-cli-setting-compaction.1
    generated/man/man1/couchbase-cli-setting-index.1
    generated/man/man1/couchbase-cli-setting-ldap.1
    generated/man/man1/couchbase-cli-setting-query.1
    generated/man/man1/couchbase-cli-setting-saslauthd.1
    generated/man/man1/couchbase-cli-setting-notification.1
    generated/man/man1/couchbase-cli-setting-password-policy.1
    generated/man/man1/couchbase-cli-setting-rebalance.1
    generated/man/man1/couchbase-cli-setting-security.1
    generated/man/man1/couchbase-cli-setting-xdcr.1
    generated/man/man1/couchbase-cli-ssl-manage.1
    generated/man/man1/couchbase-cli-user-change-password.1
    generated/man/man1/couchbase-cli-user-manage.1
    generated/man/man1/couchbase-cli-xdcr-replicate.1
    generated/man/man1/couchbase-cli-xdcr-setup.1
    generated/man/man1/couchbase-cli.1
    generated/man/man1/cblogredaction.1
    DESTINATION share/man/man1)
ENDIF ()
