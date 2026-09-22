<div align="center">

contributions

</div>

---

pull requests to other people's projects, newest first. or sorted by [repo stars](stars.md).

<dl>
<dt>★ 26.2k+ &nbsp; <a href="https://github.com/Devolutions/UniGetUI">Devolutions/UniGetUI</a> · merged · sep 2026</dt>
<dd><a href="https://github.com/Devolutions/UniGetUI/pull/5416">#5416</a> · with vcpkg enabled on macos or linux, every start reported git missing with git right on the path and offered a winget command that cannot run there; the check looked for <code>git.exe</code>, which a posix path never has. reproduced with a real vcpkg on fedora, made the check find the platform's git and the install button use the platform's own package manager through the app's elevator, and kept the windows strings byte for byte</dd>
<dt>★ 29.0k+ &nbsp; <a href="https://github.com/ente/ente">ente/ente</a> · merged · sep 2026</dt>
<dd><a href="https://github.com/ente/ente/pull/13069">#13069</a> · copying a photo with key material of the wrong length, or not base64 at all, went through and left a billed file in the album that no client could decrypt, the one endpoint missed when its three siblings got the check hours earlier; found it by probing that fix on a live server with postgres and minio, made copy reject the same items with the same 400, and filed the issue and the fix together</dd>
<dt>★ 11.3k+ &nbsp; <a href="https://github.com/kornia/kornia">kornia/kornia</a> · merged · sep 2026</dt>
<dd><a href="https://github.com/kornia/kornia/pull/4628">#4628</a> · clahe crashed on every non-square grid; found two spots that indexed one axis with the other axis's tile count, the second hidden behind the first, and checked the fix against an exact per-pixel reference</dd>
<dt>★ 770+ &nbsp; <a href="https://github.com/gotempsh/temps">gotempsh/temps</a> · merged · sep 2026</dt>
<dd><a href="https://github.com/gotempsh/temps/pull/1025">#1025</a> · a build step that ran out of memory ended in a bare <code>exit code: 1</code> after minutes of silence; reproduced on a 4 gb docker host, found the per-build memory cap had never applied under buildkit, made the deployer say so and attribute kernel oom kills to the right build</dd>
<dt>★ 6.3k+ &nbsp; <a href="https://github.com/glpi-project/glpi">glpi-project/glpi</a> · merged · sep 2026</dt>
<dd><a href="https://github.com/glpi-project/glpi/pull/25546">#25546</a> · the changes and problems tabs hid every item a "see (author)" user was requester, observer or assigned on; fixed the join comparing ids to a string, checked on live mariadb and mysql</dd>
<dt>★ 6.3k+ &nbsp; <a href="https://github.com/glpi-project/glpi">glpi-project/glpi</a> · merged · sep 2026</dt>
<dd><a href="https://github.com/glpi-project/glpi/pull/25544">#25544</a> · software dictionary replay crashed on a duplicate key whenever a merged version was already installed on the same item; fixed the join meant to clear those duplicates, checked on live mariadb and mysql</dd>
<dt>★ 28+ &nbsp; <a href="https://github.com/cubrid-lab/cubrid-cookbook-python">cubrid-lab/cubrid-cookbook-python</a> · merged · sep 2026</dt>
<dd><a href="https://github.com/cubrid-lab/cubrid-cookbook-python/pull/141">#141</a> · run every flask and fastapi recipe suite against live cubrid 11.2 and 11.4 in ci</dd>
<dt>★ 28+ &nbsp; <a href="https://github.com/cubrid-lab/cubrid-cookbook-python">cubrid-lab/cubrid-cookbook-python</a> · merged · sep 2026</dt>
<dd><a href="https://github.com/cubrid-lab/cubrid-cookbook-python/pull/132">#132</a> · fastapi recipe tests against live cubrid; fixed the startup crash from redundant primary key indexes, a missing dependency and a broken documented test command</dd>
<dt>★ 2.8k+ &nbsp; <a href="https://github.com/rlaope/oh-my-hermes">rlaope/oh-my-hermes</a> · merged · sep 2026</dt>
<dd><a href="https://github.com/rlaope/oh-my-hermes/pull/1601">#1601</a> (carried from <a href="https://github.com/rlaope/oh-my-hermes/pull/1598">#1598</a>) · fanout dispatch's linux write fence had never started; made it start and hold, and closed a <code>systemd-run</code> escape found along the way</dd>
<dt>★ 28+ &nbsp; <a href="https://github.com/cubrid-lab/cubrid-cookbook-python">cubrid-lab/cubrid-cookbook-python</a> · merged · sep 2026</dt>
<dd><a href="https://github.com/cubrid-lab/cubrid-cookbook-python/pull/134">#134</a> · flask recipe tests against live cubrid; fixed a months-old regression that had three recipes returning http 500</dd>
</dl>
