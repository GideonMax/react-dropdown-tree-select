# Snapshot report for `src/tags/index.test.js`

The actual snapshot is saved in `index.test.js.snap`.

Generated by [AVA](https://avajs.dev).

## renders tags

> Snapshot 1

    <ul
      className="tag-list"
    >
      <li
        className="tag-item"
        key="tag-item-i1"
      >
        <Tag
          id="i1"
          label="l1"
        />
      </li>
      <li
        className="tag-item"
        key="tag-item-i2"
      >
        <Tag
          id="i2"
          label="l2"
        />
      </li>
      <li
        className="tag-item"
      >
        <Input />
      </li>
    </ul>

## renders tags when no tags are passed

> Snapshot 1

    <ul
      className="tag-list"
    >
      <li
        className="tag-item"
      >
        <Input />
      </li>
    </ul>

## renders tags when no tags are passed nor Input

> Snapshot 1

    <ul
      className="tag-list"
    >
      <li
        className="tag-item"
      >
        <span
          className="placeholder"
        >
          Choose...
        </span>
      </li>
    </ul>

## should render data attributes

> Snapshot 1

    <ul
      className="tag-list"
    >
      <li
        className="tag-item test"
        "data-first"="john"
        "data-last"="smith"
        key="tag-item-i1"
      >
        <Tag
          id="i1"
          label="l1"
        />
      </li>
      <li
        className="tag-item"
      >
        <Input />
      </li>
    </ul>

## should render the tagLabel instead of label when provided

> Snapshot 1

    <ul
      className="tag-list"
    >
      <li
        className="tag-item"
        key="tag-item-i1"
      >
        <Tag
          id="i1"
          label="custom label"
        />
      </li>
      <li
        className="tag-item"
        key="tag-item-i2"
      >
        <Tag
          id="i2"
          label="l2"
        />
      </li>
      <li
        className="tag-item"
      >
        <Input />
      </li>
    </ul>
