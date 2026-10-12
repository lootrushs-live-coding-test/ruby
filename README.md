# Ruby - Escrow release

15-minute coding exercise: release funds from an escrow to the seller.

## Task

Implement `Ledger#release` in `ledger.rb`.

Full rules are in [task.md](task.md).

## Workflow

1. Create or switch to `develop`:

```bash
git switch -c develop
# or: git switch develop
```

2. Implement the task. Leave `main` unchanged.

3. Commit on `develop`:

```bash
git add -A
git commit -m "Implement escrow release"
```

4. Push and open a pull request into `main` titled **Implement escrow release**:

```bash
git push -u origin develop
```

## Verify

From the repository root:

```bash
ruby test_ledger.rb
```

`ruby test_ledger.rb` passes.

