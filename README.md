# <img src="https://avatars.githubusercontent.com/u/144374735" style="height: 30px;"> foss-[hydraulisc](https://hydraulisc.net)
Hydraulisc; Open Source, privay focused, image-sharing Social Media.

# Currently in [Private Alpha Testing/Beta Private Testing (PAT/BPT)](https://pbt.hydraulisc.net) phase! Check the [Discord](https://discord.gg/Syn5GVDemH) for more info.

- [Info regarding repository](https://blog.hydraulisc.xyz/?entry=E0Mczt2lGeyib93YSqhB)
- [Roadmap](https://blog.hydraulisc.xyz/?entry=haulisc-roadmap)
- [Hydraulisc's About Site](https://about.hydraulisc.net)
- [Discord](https://discord.gg/Syn5GVDemH)

## Warning!
If you are migrating from Hydraulisc version 1.3 or earlier, you need to perform v1 database migrations!

`node migrate-database-v1.js`

If you are migrating from version 1.3 to a newer version you need to perform v2 database migrations to support discriminators!

`node migrate-database-v2.js`

<details>
<summary>Quick References:</summary>
<ul>
    <li><b>CSS</b>: snake_case</li>
    <li><b>JS</b> and <b>file names</b>: camelCase</li>
</ul>
</details>

<details>
<summary>Features (WIP):</summary>
<ul>
    <li>Privacy Focused</li>
    <li>Username-only accounts for anonimity</li>
    <li>Private, Invite-Only or Public modes</li>
    <li>Direct Invite links</li>
    <li>Uploaded files mimetype checks</li>
    <li>XSS Upload Preventions (sanitize text before upload)</li>
    <li>XSS Rendering Preventions (sanitize and render)</li>
</ul>
</details>