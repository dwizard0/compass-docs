# Getting Started

This guide walks you through setting up your ship in COMPASS from scratch. The entire process takes about five minutes and is largely automatic — COMPASS pulls your ship data and crew roster directly from the SFI Members Portal.

---

## Before You Begin

You'll need:

- Your **db.sfi.org username and password** (your SFI database credentials — not a COMPASS password)
- To be listed as **CO or XO** of your chapter in db.sfi.org — the setup will fail if you're not

!!! note "These are your SFI credentials, not a COMPASS account"
    COMPASS uses your db.sfi.org credentials **once** to pull your chapter info and roster. They are never stored. If you don't have db.sfi.org credentials, log in at [db.sfi.org](https://db.sfi.org) first to set them up.

---

## Step 1 — Enter Your SFI Credentials

Go to **[compass.sfi.org/ship-setup](https://compass.sfi.org/ship-setup)**.

You'll see the **Add Your Ship to COMPASS** screen asking for your db.sfi.org username and password.

Enter your credentials and click **Connect to SFI**. COMPASS will authenticate against the SFI database and fetch your chapter information and roster. This takes a few seconds — a loading spinner will appear while it works.

!!! warning "Only CO or XO can run setup"
    COMPASS verifies your role against db.sfi.org. If you're not listed as CO or XO, you'll see an error: *"Only the Commanding Officer or Executive Officer can set up a ship in COMPASS."* Have your CO or XO run the setup instead.

**Common errors at this step:**

- *"Unable to authenticate"* — double-check your db.sfi.org username and password. Log into db.sfi.org directly first to confirm they work.
- *"Unable to retrieve chapter information"* — your account authenticated but has no CO/XO role on file. Contact your RC.

---

## Step 2 — Select Your Chapter (if prompted)

If your SFI account is associated with **more than one chapter**, COMPASS will show you a chapter selection screen. Pick the chapter you're setting up and continue.

If you only have one chapter, this step is skipped automatically.

---

## Step 3 — Review Your Ship Information

COMPASS will display a **Review & Confirm** page showing everything it pulled from db.sfi.org:

**Ship Information**

- Ship name and registry
- Ship class
- Region
- Chapter type
- Commissioned date and charter city

**Command Staff**

- CO name and SCC — with a "You" badge next to your name
- XO name and SCC

**Crew Roster Preview**

A table showing every member COMPASS found in your db.sfi.org roster, with their position, rank, name, and SCC. This is a preview — nothing has been saved yet.

**Review this carefully.** If the ship name, registry, or command staff looks wrong, click **← Start Over** and contact your RC — the data comes directly from db.sfi.org, so any errors need to be corrected there first.

!!! warning "Ship already exists in COMPASS"
    If your ship has already been set up by someone else, you'll see an orange warning on this page and the Create Ship button won't appear. Contact your RC to get access to your ship's existing record.

---

## Step 4 — Create Ship & Import Crew

If everything looks correct, click **Create Ship & Import Crew**.

COMPASS will:

1. **Create your ship record** — name, registry, class, region, and all chapter details
2. **Import your entire crew roster** — all members from db.sfi.org are added to COMPASS with their ranks, positions, and SCC numbers
3. **Create your COMPASS account** — you're automatically logged in after setup
4. **Sync your eligibility data** — your OTS/OCC completions and academy records are pulled from db.sfi.org

!!! note "Don't close the page"
    A loading spinner appears while provisioning runs. This can take 10–15 seconds depending on roster size. **Don't close or refresh the page** while it's working.

---

## Step 5 — You're In

On success, COMPASS redirects you to the **Ship Dashboard** with a confirmation message:

> *"Welcome to COMPASS! USS [Your Ship] (NCC-XXXXX) has been successfully set up. Imported X new crew and updated Y existing."*

Your ship is now live in COMPASS with your full roster already imported.

---

## After Setup — What to Do Next

Your ship is operational, but there are a few things worth doing immediately:

### Set Your Password

Your COMPASS account was created automatically with a temporary password. Go to **Profile → Change Password** and set a real one before logging out.

### Verify Your Roster

Go to **Crew** and scan through your imported roster. Check that:

- All active members are present
- Ranks look correct
- Anyone who has left SFI or transferred is marked accordingly (see [Managing Your Roster](roster.md))

The import pulls directly from db.sfi.org, so if someone is missing it means they weren't on your chapter's roster there.

### Invite Your XO

Your XO was imported as a crew member but may not have a COMPASS account yet. Direct them to [compass.sfi.org](https://compass.sfi.org) to register — they'll need to create an account with the same SCC on file. Once their account is active, their CO/XO permissions will apply automatically.

### Log Your First Event

Go to **Events → Create Event** and enter your most recent ship meeting. See the [Events Guide](events.md).

---

## Troubleshooting

**Setup failed partway through.**
The setup runs as a single transaction — if anything fails, nothing is saved. You can safely run it again from the start. Check the error message for specifics and contact your RC if it persists.

**My roster shows 0 members.**
Your chapter may not have a roster on file in db.sfi.org, or there may be a formatting issue with the data. Your ship record will still be created — you can add crew manually afterward through **Crew → Add Member**.

**I already have a COMPASS account but I'm running setup.**
That's fine — COMPASS will detect your existing account (matched by SCC) and link it to the new ship rather than creating a duplicate.

**My ship was previously in COMPASS but was withdrawn.**
COMPASS handles this automatically. If your ship's registry matches a withdrawn ship in the system, setup will **reactivate** it rather than create a duplicate. Your historical data (awards, promotion history, events) is fully preserved. Crew members won't be auto-restored — they'll need to rejoin through the normal join request process.
