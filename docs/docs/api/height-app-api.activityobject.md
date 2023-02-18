---
id: height-app-api.activityobject
title: ActivityObject type
hide_title: true
displayed_sidebar: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[height-app-api](./height-app-api.md) &gt; [ActivityObject](./height-app-api.activityobject.md)

## ActivityObject type

**Signature:**

```typescript
export type ActivityObject = {
    id: string;
    model: string;
    createdAt: string;
    taskId: string;
    createdUserId: string;
    type: 'comment' | 'description' | 'createdAt' | 'statusChange' | 'statusRemoved' | 'assigneeChange' | 'listsChange' | 'nameChange' | 'customFieldChange' | 'fieldOptionRemoved';
    message?: string;
    oldValue?: string;
    newValue?: string;
    reactjis: Array<{
        id?: string;
        model?: string;
        emoji?: string;
        userId?: string;
        activityId?: string;
    }>;
    readUserIds: Array<string>;
    url: string;
};
```