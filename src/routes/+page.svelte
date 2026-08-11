<script>
    import { version, currentSize } from "$lib/index";
</script>

<div class="w-full min-h-screen flex justify-center items-center">
    <div class="flex flex-col">
        <div class="flex justify-center items-center">
            <h1 class="text-2xl font-semibold text-violet-600">
                Lara

                <span class="bg-violet-600 text-white p-2">Editor</span>
            </h1>
        </div>

        <span class="text-sm text-center text-slate-500 m-3">Version {version} • {currentSize} MB</span>
    </div>
</div>

