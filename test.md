<!--
  Pull request review checklist
 -->

<details>
  <summary>🚀 Pull Request (PR) checklist for Reviewer</summary>

## General

- [ ] Add the PR to iX Project (status: In progress)
- [ ] No auto generated code is modified without editing source files

## Versioning

- [ ] Assign semantic version label `patch`, `minor` or `major` to the pull request
- [ ] Assign a milestone to the PR
- [ ] If the PR contains api change (Prop, Event, Method) of the component besure that the `@since x.x.x` is correct added to the jsdocs comment depending of the added milestone. e.g.

```typescript

/**
 * ...
 *
 * @since 1.2.0
 * /
Prop() xyz: string;

```

- [ ] If a custom css variable name is changed for a component it is count as `major` change and should be discussed inside the weekly jour fix. (Add "jour fix @dev" tag and change status to "Jour Fix")
- [ ] If a custom css variable name is changed be aware that this change have also affects inside the internal brand theme

## Visual regression testing

- [ ] Add Visual regression test also for the `@siemens/ix-brand-theme`

</details>
