<script>
    export let title = 'Tilawah | Al-Quran Digital Terlengkap dengan Latin dan Terjemahan Bahasa Indonesia',
    url = '',
    description = 'Tilawah adalah situs Al-Quran lengkap dengan transliterasi dan terjemahan bahasa Indonesia.',
    image = '/favicon.png',
    keywords = '';
</script>

<svelte:head>
    <title>{title}</title>
    <meta name="title" content={title}>
    <meta name="description" content={description}>
    <meta name="keywords" content="al-quran digital, website al-quran, aplikasi al-quran, al-quran, {keywords.toLowerCase()}">
    <meta name="robots" content="index, follow">
    <meta name="language" content="Bahasa Indonesia">
    <meta name="author" content="Juan Akbary">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta property="og:title" content={title}>
    <meta property="og:site_name" content="Tilawah">
    <meta property="og:url" content={url}>
    <meta property="og:description" content={description}>
    <meta property="og:type" content="website">
    <meta property="og:image" content={image}>
    <meta property="og:locale" content="id_ID" />
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content={url}>
    <meta property="twitter:title" content={title}>
    <meta property="twitter:description" content={description}>
    <meta property="twitter:image" content={image}>
</svelte:head>