project(samseg)

install_configured(samseg samseg-long DESTINATION bin)
install_pyscript(
  run_samseg
  run_samseg_long
  sbtiv
  gems_compute_binary_atlas_probs
)
