<script>
    import { version, currentSize } from "$lib";
</script>

<div class="flex flex-col space-y-3">
    <div class="flex justify-center items-center">
        <h1 class="text-3xl font-semibold text-violet-600">
            Lara

            <span class="bg-violet-600 text-white py-1 px-2 rounded-md">Editor</span>
        </h1>
    </div>

    <span class="text-sm text-center text-slate-500"
        >Version {version} • {currentSize} MB</span
    >
</div>
