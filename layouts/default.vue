<template>
    <ul>
        <li>
            <NuxtLink to="/">home</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/about">about</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/article">artikel</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/auth/login">login</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/auth/register">register</NuxtLink>
        </li>
    </ul>
    <div>
        <slot></slot>
    </div>
</template>