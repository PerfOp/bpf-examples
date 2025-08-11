tx mode:
  sudo ./xdpsock -i ${local_eth_name} -q 0 -t --tx-dmac="${target_mac}" --tx-smac="${src_mac}" -g "${target_ip}" -h "${src_ip}" -a
rx mode:
  sudo ./xdpsock -i ${local_eth_name} -q 0 -r -a
