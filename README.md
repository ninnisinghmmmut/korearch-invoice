# Korearch Infrastructure — GST Tax Invoice Generator

A single-file, offline-capable web app to generate **GST-compliant printable tax invoices**
(Indian tax norms) for **Korearch Infrastructure Private Limited** — a construction &
architecture firm based in Gorakhpur, Uttar Pradesh.

## Live app
Once GitHub Pages is enabled, the app is available at:
`https://<your-username>.github.io/<repo-name>/`

## Features
- Auto **CGST + SGST** (intra-state) vs **IGST** (inter-state), decided by Place of Supply
- Per-line **SAC codes** and GST rates (0/1/5/12/18/28%) with construction/architecture presets
- Rate-wise tax summary, round-off, and **amount in words** (Indian crore/lakh)
- B2B & B2C/unregistered clients, reverse charge, discounts, ship-to, project/PO fields
- Bank details, terms, authorised-signatory block
- **Print / Save as PDF** from the browser; saves firm & bank details locally for reuse

## Usage
Open `index.html` in any modern browser (no install, no internet needed). Fill the form and
click **Print / Save as PDF**.

> **Note:** GSTIN, PAN, CIN, invoice number and bank details ship as placeholders (marked ▲).
> Replace them with your real details before issuing an invoice — a tax invoice is not valid
> without a correct 15-digit GSTIN.
