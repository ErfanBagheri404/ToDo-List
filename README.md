# ToDo List

Vanilla-JS todo list: add items, mark them complete, delete them, and filter by
all / completed / uncompleted. Everything is persisted in `localStorage`, so the
list survives a reload.

## Features

- Add via the input + button (empty input is ignored).
- Click an item to toggle completion; the trash icon deletes it.
- `select` filter switches the visible set without touching the data.
- `DOMContentLoaded` -> `getLocalTodos()` restores the saved list.

## Live demo

https://erfan-revenant.github.io/ToDo-List/

## Run

```bash
git clone https://github.com/ErfanBagheri404/ToDo-List.git
cd ToDo-List
```

Open `index.html`.

## Files

| file | role |
|---|---|
| `index.html` | input, filter select, empty list |
| `index.js` | add / complete / delete / filter + localStorage |
| `style.css` | layout, transitions, icons |
