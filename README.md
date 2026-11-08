# PMC Certificate Maker

Automatic certificate generator of the First Philippine Model Congress - ISPSC (Bachelor of Public Administration, College of Business, Management, and Entrepreneurship, Ilocos Sur Polytechnic State College).

| Path | What it is |
|---|---|
| `index.html` | The Certificate Maker: Completion, Participation (Representation, Committee, Plenary), Appreciation, Best Committee, Ten Best Speakers, Best Policy and Special Policy Awards, and Individual Awards |
| `.nojekyll` | Tells GitHub Pages to serve the file as it is |

Everything is inside `index.html`: fonts, logos, seals, signature, roster, and the PDF tools. No internet connection is needed after the page loads.

## Step-by-step: publishing on GitHub Pages

1. **Unzip** the package on a laptop or desktop.
2. **Sign in** at github.com.
3. **Create a repository:** click **+** (upper right) > **New repository**. Name it, for example, `pmc-certificates`. Choose **Public** (needed for GitHub Pages on a free account). Leave "Add a README file" unchecked. Click **Create repository**.
4. **Upload:** click **uploading an existing file**. Drag in `index.html` and `README.md` (and `.nojekyll` if your computer shows it). Click **Commit changes**.
5. **Turn on Pages:** **Settings** > **Pages** > Source: *Deploy from a branch*, Branch: `main`, folder `/ (root)` > **Save**.
6. **Open the site** after 1 to 2 minutes: `https://YOUR-USERNAME.github.io/pmc-certificates/`
7. **Sign in** with the access password: `PMC-CERT-2026`.

## Using it

- Choose a certificate type on the left. Each type has **Print all (one file)**, **Download all as one PDF**, and **Download individual PDFs (ZIP)**. Every certificate also has its own **PDF** and **Print** buttons.
- **Winners** (Best Committee, Ten Best Speakers, Best Policy, Individual Awards) are saved only in the browser where you choose them. Nobody else who opens the link can see your choices, so the awards stay a surprise. Use the same browser on the same computer when you print.
- **Printing:** Chrome or Edge, Landscape, Margins **None**, Scale **100%**, **Background graphics** on.

## Updating

To change the roster, designs, or password, replace `index.html` in the repository: **Add file** > **Upload files** > upload the new `index.html` > **Commit changes**.

## Important

- **The password is not real security.** The page is a public file, so a person with technical skill can read its contents, including the e-signature image. The password only keeps casual visitors out. Share the link only with people who need it, and consider deleting the repository (Settings > Danger Zone) after the certificates are printed.
- The page has a `noindex` tag so search engines do not list it.
- Certificates are for the First Philippine Model Congress - ISPSC only. The e-signature must not be used on any other document.
