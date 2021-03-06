v5.0.0 (2020-04-21)
===================

- Migrate GCE to Google API.
  [\#242](https://github.com/SUSE-Enceladus/ipa/pull/242)

v4.8.1 (2020-03-10)
===================

- Fix bug and check both CLI output versions for single
  and double quote.

v4.8.0 (2020-03-10)
===================

- Attempt to cleanup instance if error during launch.
  [\#234](https://github.com/SUSE-Enceladus/ipa/pull/234)
- Add distro refresh option.
  [\#235](https://github.com/SUSE-Enceladus/ipa/pull/235)
- Use systemctl to check guestregister status.
  [\#236](https://github.com/SUSE-Enceladus/ipa/pull/236)
- Log only to base logger.
  [\#239](https://github.com/SUSE-Enceladus/ipa/pull/239)
- Handle HPC on-demand repos.
  [\#240](https://github.com/SUSE-Enceladus/ipa/pull/240)
- Add timestamp to file log handler.
  [\#241](https://github.com/SUSE-Enceladus/ipa/pull/241)

v4.7.0 (2020-02-18)
===================

- Cleanup spec file.
  [\#230](https://github.com/SUSE-Enceladus/ipa/pull/230)
- Add list of 15-SP2 repos to SLES on-demand repo test.
  [\#232](https://github.com/SUSE-Enceladus/ipa/pull/232)

v4.6.0 (2020-1-21)
===================

- Edit sap license test to handle 12SP5.
  [\#226](https://github.com/SUSE-Enceladus/ipa/pull/226)
- Skip kernel test if not a latest image version.
  [\#227](https://github.com/SUSE-Enceladus/ipa/pull/227)
- Generate man pages in build with click-man.
  [\#228](https://github.com/SUSE-Enceladus/ipa/pull/228)
- Implement Oracle cloud class (oci).
  [\#229](https://github.com/SUSE-Enceladus/ipa/pull/229)

v4.5.1 (2019-10-28)
===================

- Use sudo with registration command for non root users.
  [\#225](https://github.com/SUSE-Enceladus/ipa/pull/225)

v4.5.0 (2019-10-25)
===================

- Use registerutils functions to check registration.
  [\#224](https://github.com/SUSE-Enceladus/ipa/pull/224)

v4.4.0 (2019-10-14)
===================

- Remove region filter from smt registration test.
  [\#223](https://github.com/SUSE-Enceladus/ipa/pull/223)

v4.3.1 (2019-08-21)
===================

- Remove azure regions map from smt reg test.
- Update get\_smt\_servers to not filter type in smt reg
  test.
  [\#221](https://github.com/SUSE-Enceladus/ipa/pull/221)

v4.3.0 (2019-08-13)
===================

- Move get user data method to base class.
  [\#215](https://github.com/SUSE-Enceladus/ipa/pull/215)
- Update sles repos test for rmt.
  [\#217](https://github.com/SUSE-Enceladus/ipa/pull/217)
- Add repos for sles12-sp5.
  [\#218](https://github.com/SUSE-Enceladus/ipa/pull/218)
- Print serial console output to log.
  [\#219](https://github.com/SUSE-Enceladus/ipa/pull/219)
- Add case for checking kernel config version.
  [\#220](https://github.com/SUSE-Enceladus/ipa/pull/220)

v4.2.1 (2019-07-18)
===================

- Consider location restrictions retryable in GCE.
  [\#212](https://github.com/SUSE-Enceladus/ipa/pull/212)
- Wait longer on soft reboot.
  [\#213](https://github.com/SUSE-Enceladus/ipa/pull/213)
- Add test for azure launch exception.
  [\#213](https://github.com/SUSE-Enceladus/ipa/pull/213)

v4.2.0 (2019-07-16)
===================

- Use the "baseproduct" link as indicator of the SLES product.
  [\#208](https://github.com/SUSE-Enceladus/ipa/pull/208)
- Remove support for py3.4.
  [\#210](https://github.com/SUSE-Enceladus/ipa/pull/210)
- Indicate retryable error (GCE only).
  [\#211](https://github.com/SUSE-Enceladus/ipa/pull/211)

v4.1.1 (2019-07-01)
===================

- Run reboot in background process.
  [\#207](https://github.com/SUSE-Enceladus/ipa/pull/207)
- Make tox env work with python3.7.
  [\#209](https://github.com/SUSE-Enceladus/ipa/pull/209)

v4.1.0 (2019-06-06)
===================

- Make license test fixture generic.
  [\#206](https://github.com/SUSE-Enceladus/ipa/pull/206)

v4.0.0 (2019-05-30)
===================

- Clear ssh cache at start of module.
  [\#196](https://github.com/SUSE-Enceladus/ipa/pull/196)
- Move set_distro to beginning of method.
  [\#199](https://github.com/SUSE-Enceladus/ipa/pull/199)
- Attempt to cleanup instance on ssh fail.
  [\#200](https://github.com/SUSE-Enceladus/ipa/pull/200)
- Echo log file if results file provided.
  [\#201](https://github.com/SUSE-Enceladus/ipa/pull/201)
- Rename ipa to img-proof.
  [\#202](https://github.com/SUSE-Enceladus/ipa/pull/202)

v3.3.1 (2019-05-07)
===================

- Add stable release repository for ipa.
  [\#189](https://github.com/SUSE-Enceladus/ipa/pull/189)
- Check default dirs exist in ipa list.
  [\#191](https://github.com/SUSE-Enceladus/ipa/pull/191)
- Add retry on ec2 image download.
  [\#192](https://github.com/SUSE-Enceladus/ipa/pull/192)

v3.3.0 (2019-03-26)
===================

- Cast timeout to integer.
  [\#184](https://github.com/SUSE-Enceladus/ipa/pull/184)
- Fix Azure service test on SLES 11.
  [\#185](https://github.com/SUSE-Enceladus/ipa/pull/185)
- Combine libcloud class with GCE.
  [\#186](https://github.com/SUSE-Enceladus/ipa/pull/186)
- Cleanup gce tests.
  [\#187](https://github.com/SUSE-Enceladus/ipa/pull/187)
- Rename ipa cloud test module.
  [\#188](https://github.com/SUSE-Enceladus/ipa/pull/188)

v3.2.1 (2019-03-15)
===================

- EC2 instances may have ipv6 addresses set to None.
  [\#183](https://github.com/SUSE-Enceladus/ipa/pull/183)

v3.2.0 (2019-03-14)
===================

- Add repos for 15sp1.
  [\#174](https://github.com/SUSE-Enceladus/ipa/pull/174)
- Use pytest fail instead of raise exception.
  [\#175](https://github.com/SUSE-Enceladus/ipa/pull/175)
- Make ec2 network test more expressive.
  [\#177](https://github.com/SUSE-Enceladus/ipa/pull/177)
- Add replacefiles option to zypper update.
  [\#181](https://github.com/SUSE-Enceladus/ipa/pull/181)
- Use format string for motd check.
  [\#182](https://github.com/SUSE-Enceladus/ipa/pull/182)

v3.1.1 (2019-02-28)
===================

- Add new license directories for SLES test.
  [\#173](https://github.com/SUSE-Enceladus/ipa/pull/173)

v3.1.0 (2019-02-22)
===================

- Check for ssh key file separately in ec2.
  [\#169](https://github.com/SUSE-Enceladus/ipa/pull/169)
- Add specific commands for GCE credentials setup.
  [\#170](https://github.com/SUSE-Enceladus/ipa/pull/170)
- SSH user key in ec2utils config is user.
  [\#171](https://github.com/SUSE-Enceladus/ipa/pull/171)
- Accept availability zones as ec2 region.
  [\#172](https://github.com/SUSE-Enceladus/ipa/pull/172)

v3.0.0 (2019-02-04)
===================

- Add missing security group id to ssh class.
  [\#161](https://github.com/SUSE-Enceladus/ipa/pull/161)
- Add collect vm info to gce class super call.
  [\#162](https://github.com/SUSE-Enceladus/ipa/pull/162)
- Cleanup ini config handling.
  [\#163](https://github.com/SUSE-Enceladus/ipa/pull/163)
- Allow use of ipa config for provider options.
  [\#164](https://github.com/SUSE-Enceladus/ipa/pull/164)
- Compare wait on instance states as lowercase.
  [\#165](https://github.com/SUSE-Enceladus/ipa/pull/165)
- Remove references to provider with cloud, cloud frameworks.
  [\#166](https://github.com/SUSE-Enceladus/ipa/pull/166)
- Don't pass unused args to cloud classes.
  [\#167](https://github.com/SUSE-Enceladus/ipa/pull/167)

v2.6.0 (2019-01-04)
===================

- Remove duplication when logging.
  [\#156](https://github.com/SUSE-Enceladus/ipa/pull/156)
- Allow azure instance to start in existing subnet.
  [\#158](https://github.com/SUSE-Enceladus/ipa/pull/158)
- Treat uuid always lowercase.
  [\#159](https://github.com/SUSE-Enceladus/ipa/pull/159)
- Use base provider waiter method.
  [\#160](https://github.com/SUSE-Enceladus/ipa/pull/160)

v2.5.0 (2018-12-11)
===================

- Add note on installing SLES test suite.
  [\#148](https://github.com/SUSE-Enceladus/ipa/pull/148)
- Add option allowing collect info about VM in cloud.
  [\#149](https://github.com/SUSE-Enceladus/ipa/pull/149)
- With running instance don't cleanup.
  [\#152](https://github.com/SUSE-Enceladus/ipa/pull/152)
- Systemd cleanup in distro.
  [\#153](https://github.com/SUSE-Enceladus/ipa/pull/153)
- Process pytest errors in results.
  [\#154](https://github.com/SUSE-Enceladus/ipa/pull/154)
- Switch EC2 provider back to boto3.
  [\#155](https://github.com/SUSE-Enceladus/ipa/pull/155)

v2.4.0 (2018-12-06)
===================

- Auto deploy IPA package in pypi on new tag release.
  [\#139](https://github.com/SUSE-Enceladus/ipa/pull/139)
- Add security-group-id option for ec2 provider.
  [\#151](https://github.com/SUSE-Enceladus/ipa/pull/151)

v2.3.0 (2018-11-09)
===================

- Move docs to sphinx.
  [\#141](https://github.com/SUSE-Enceladus/ipa/pull/141)
- Update python version support.
  [\#142](https://github.com/SUSE-Enceladus/ipa/pull/142)
- Allow ipa to run without config file.
  [\#137](https://github.com/SUSE-Enceladus/ipa/pull/137)
- No need for gpg auto import keys.
  [\#144](https://github.com/SUSE-Enceladus/ipa/pull/144)
- Add --name option to az creds example.
  [\#145](https://github.com/SUSE-Enceladus/ipa/pull/145)
- Explicit validation of GCE region input.
  [\#146](https://github.com/SUSE-Enceladus/ipa/pull/146)
- Update license tests for content changes.
  [\#147](https://github.com/SUSE-Enceladus/ipa/pull/147)

v2.2.0 (2018-10-31)
===================

- Add network test for sles in ec2.
  [\#134](https://github.com/SUSE-Enceladus/ipa/pull/134)
- Remove azure billing tag test.
  [\#136](https://github.com/SUSE-Enceladus/ipa/pull/136)
- Fix typo in azure services test name.
  [\#138](https://github.com/SUSE-Enceladus/ipa/pull/138)
- Add python3.7 to CI testing.
  [\#140](https://github.com/SUSE-Enceladus/ipa/pull/140)
- Add repos for 12SP4 in conftest
  [\#143](https://github.com/SUSE-Enceladus/ipa/pull/143)

v2.1.0 (2018-10-01)
===================

- Add IPA logo.
- Cloud init services are one-shot in EC2.
  [\#131](https://github.com/SUSE-Enceladus/ipa/pull/131)
- Add azure accelerated networking option.
  [\#132](https://github.com/SUSE-Enceladus/ipa/pull/132)
- Curl directly for placement in metadata when determining
  region.
  [\#133](https://github.com/SUSE-Enceladus/ipa/pull/133)

v2.0.1 (2018-09-12)
===================

- Update project status to stable.
- Update root pass test to work with SLE11.
  [\#125](https://github.com/SUSE-Enceladus/ipa/pull/125)
- Account for sysvinit in SLE11.
  [\#126](https://github.com/SUSE-Enceladus/ipa/pull/126)
- Convert azure regions from id to display format.
  [\#127](https://github.com/SUSE-Enceladus/ipa/pull/127)
- Update repo URL to correct org.
  [\#128](https://github.com/SUSE-Enceladus/ipa/pull/128)

v2.0.0 (2018-08-15)
===================

- Remove deprecated --ssh-private-key option.
  Option was renamed to --ssh-private-key-file.

v1.4.0 (2018-08-15)
===================

- Add archive management option to CLI.
  [\#83](https://github.com/SUSE-Enceladus/ipa/pull/83)
- openSUSE Leap requires auto import of repo keys.
  [\#98](https://github.com/SUSE-Enceladus/ipa/pull/98)
- Update Leap test description.
  [\#99](https://github.com/SUSE-Enceladus/ipa/pull/99)
- Sync tests should not raise exception.
  [\#100](https://github.com/SUSE-Enceladus/ipa/pull/100)
- Use the GCE service account in the launched instance.
  [\#107](https://github.com/SUSE-Enceladus/ipa/pull/107)
- Add serviceAccountUser role requirement for GCE.
- Rename pretty\_name to be generic value.
  [\#108](https://github.com/SUSE-Enceladus/ipa/pull/108)
- Use temp directory for results in tests.
  [\#109](https://github.com/SUSE-Enceladus/ipa/pull/109)
- Move docs to markdown for better support.
  [\#110](https://github.com/SUSE-Enceladus/ipa/pull/110)
- Determine provider and region from instance.
  [\#113](https://github.com/SUSE-Enceladus/ipa/pull/113)
- Add SLE\_15 repos.
  [\#116](https://github.com/SUSE-Enceladus/ipa/pull/116)
- Update GCE services test.
  [\#117](https://github.com/SUSE-Enceladus/ipa/pull/117)
- Rename `--ssh-private-key` option.
  [\#119](https://github.com/SUSE-Enceladus/ipa/pull/119)
- Add ip address option for SSH testing.
- Add SSH provider.
  [\#115](https://github.com/SUSE-Enceladus/ipa/pull/115)

v1.3.0 (2018-07-23)
===================

- Add ec2 tests to check billing code in metadata.
  [\#81](https://github.com/SUSE-Enceladus/ipa/pull/81)
- Using token normalize breaks region shortcode. Remove region
  shortcode which overlaps running instance id.
  [\#92](https://github.com/SUSE-Enceladus/ipa/pull/92)
- Allow new paths for history log option. when testing.
  [\#95](https://github.com/SUSE-Enceladus/ipa/pull/95)
- If a test dir does not exist just continue.
  [\#104](https://github.com/SUSE-Enceladus/ipa/pull/104)
- Update GCE setup/configuration docs.
- Move requirements to txt files.
- Raise useful exception msg if GCE service account file is invalid.
  [\#106](https://github.com/SUSE-Enceladus/ipa/pull/106)
- Add certifi requirement for Libcloud GCE driver.
- Update pycrypto requirement to pycryptodome.

v1.2.0 (2018-06-14)
===================

- Add SLES test to ensure root user has no password.
  [\#90](https://github.com/SUSE-Enceladus/ipa/pull/90)
- Fix typo in force new reg test.
- Add \--timeout cli and configuration option.
  [\#86](https://github.com/SUSE-Enceladus/ipa/pull/86)
- Add a test to wait on registration for on-demand instances.
  [\#87](https://github.com/SUSE-Enceladus/ipa/pull/87)
- Add azure tests to check billing tag in metadata.
  [\#88](https://github.com/SUSE-Enceladus/ipa/pull/88)
- Handle custom Azure image vhd id's.
  [\#89](https://github.com/SUSE-Enceladus/ipa/pull/89)

v1.1.1 (2018-05-16)
===================

- Cleanup typo in docs.
- Explicitly close SSH connections.
  [\#79](https://github.com/SUSE-Enceladus/ipa/pull/79)

v1.1.0 (2018-05-15)
===================

- Add requirements and external test injection with the `--inject`
  option. [\#78](https://github.com/SUSE-Enceladus/ipa/pull/78)
    - Adds the option to inject packages, archives and files. Also
      provides the ability to execute commands and install packages
      from an existing repository.

v1.0.0 (2018-03-30)
===================

- Tests argument is now optional.
  [\#56](https://github.com/SUSE-Enceladus/ipa/pull/56)
    - This allows for the use of `--no-cleanup` option to start an
      instance in the given framework.
- Add regression test to check for valid UUID on SLES instance in EC2.
  [\#57](https://github.com/SUSE-Enceladus/ipa/pull/57)
- Add regression test to confirm lscpu binary returns successful exit
  code. [\#58](https://github.com/SUSE-Enceladus/ipa/pull/58)
- Subnet option has been added to launch a new instance in the given
  network/subnet (`--subnet-id`).
  [\#59](https://github.com/SUSE-Enceladus/ipa/pull/59)
- Remove requirement on case with distro and provider options.
  [\#60](https://github.com/SUSE-Enceladus/ipa/pull/60) &
  [\#65](https://github.com/SUSE-Enceladus/ipa/pull/65)
- Use Testinfra run module to check hostname. System Info module was
  removed from package. [\#61](https://github.com/SUSE-Enceladus/ipa/pull/61)
- Migrate Azure provider to the ARM (resource manager API).
  [\#63](https://github.com/SUSE-Enceladus/ipa/pull/63)
- Add option to use user-data for loading SSH public key to instance
  in EC2. [\#68](https://github.com/SUSE-Enceladus/ipa/pull/68)
- Add delete history item option to results command.
  [\#69](https://github.com/SUSE-Enceladus/ipa/pull/69)
    - Split up results command into separate subcommands.

v0.5.1 (2017-12-11)
===================

- Cleanup MANIFEST.
- Fix README.

v0.5.0 (2017-12-11)
===================

- Use cpe\_name to determine SAP product in SLES tests.
- Allow EC2 testing without a config file.
- Update README overview with more info.
- Provide log\_file and results\_file in results dict.
- Other formatting and bug fixes.

v0.4.0 (2017-10-12)
===================

- Migrate EC2 provider to apache-libcloud.
- Remove vcrpy integration tests.

v0.3.0 (2017-09-20)
===================

- Add test\_dirs to args for test endpoint.
- Fix bug if test fails before sync point.
- Add SLES update infrastructure tests.
- Add command line option \--no-default-test-dirs.
- Add skipped tests to results output.
- Update man pages and and cleanup docs.

v0.2.0 (2017-09-07)
===================

- Add test suite for testing SLES images.
- Add SLES tests to MANIFEST.
- Fix change log in MANIFEST.
- Ignore SLES tests in setup.cfg.
- Fix ipa provider test, include region and platform in results dict.
- Add tests package to spec and mv to python3-ipa.spec.
- Pass region and platform to pytest for use in tests.

v0.1.3 (2017-09-05)
===================

- Check format of unit/integration tests with flake8 in tox/travis.
- Cleanup flake8 format in azure integration test.

v0.1.2 (2017-08-31)
===================

- After soft and hard reboot ensure host key has not changed.

v0.1.1 (2017-08-30)
===================

- Python3 format spec instead of Python single spec.
- Add missing requirements for GCE to spec.

v0.1.0 (2017-08-30)
===================

- Integrate GCE provider using apache-libcloud.

v0.0.5 (2017-08-29)
===================

- Explicit ignore of tests/data directory in spec file.

v0.0.4 (2017-08-29)
===================

- Account for classes and parameterized tests.

v0.0.3 (2017-08-29)
===================

- Cleanup azure unit tests.

v0.0.2 (2017-08-22)
===================

- Update Travis to build only master + tags.
- Use deault dicts in results summary.
- Clenaup error message usage.
- Add shebang to shell script.
- Use yaml safe\_load.
- Spelling fixes.
- Cleanup spec file.

v0.0.1 (2017-08-15)
===================

- Initial release.
