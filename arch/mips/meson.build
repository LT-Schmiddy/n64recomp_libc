# mips architecture meson build

mips_arch_dep = declare_dependency(
	include_directories: include_directories('include'),
	sources: files(
		# 'src/__aeabi_atexit.c',
		# 'src/crt0.S',
	)
)

if build_arch == 'mips'
	build_machine_dep = mips_arch_dep
endif

if host_arch == 'mips'
	host_machine_dep = mips_arch_dep
endif
