<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="mr40 mt20">
                    <router-link to="/list-Article">
                        <img src="../../assets/icons/back.svg">
                    </router-link>
                </div>
                <div>
                    <h1 class="m0">Add Article</h1>
                    <p class="mt5 mb20 tc-green">Make your article looks good</p>
                </div>
            </div>
            <hr class="uline-grey">
            <div class="mt50 row">
                <div class="w20">
                    <label class="form-label">Article Image</label>
                </div>
                <div class="w80">
                    <input
                        class="form-text"
                        type="text"
                        placeholder="Input your full name"
                    >
                </div>
            </div>
            <div class="mt30 row">
                <div class="w20">
                    <label class="form-label">Article Name & Content</label>
                </div>
                <div class="w80">
                    <input
                        class="form-text"
                        type="text"
                        placeholder="Judul Article"
                    >
                    <div class="mt30 row">

                        <input
                            class="form-content"
                            type="text"
                            placeholder="Content (Min.1000Char)"
                        >
                    </div>
                </div>  
            </div>
            <div class="mt30 row">
                <div class="w20">
                    <label class="form-label">Broadcast Schedule</label>
                </div>
                <div class="w80">
                    <input
                        class="form-text"
                        type="text"
                        placeholder="pilih hari"
                    >
                </div>
            </div>
            <div class="mt30 row">
                <div class="w20">
                    <label class="form-label">Valid from</label>
                </div>
                <div class="w80">
                    <input
                        class="form-text"
                        type="text"
                        placeholder="Masukan Tanggal"
                    >
                </div>
            </div>
            <div class="mt30 row">
                <div class="w20">
                    <label class="form-label">Valid Until</label>
                </div>
                <div class="w80">
                    <input
                        class="form-text"
                        type="text"
                        placeholder="Masukan Tanggal"
                    >
                </div>
            </div>
            
            <div class="flex mt30">
                <router-link to="/list-Article">
                    <button class="bt-submit-green">Add Article</button>
                </router-link>
            </div>
        </div>
    </div>
    
</template>

<script>
export default {
	name: 'add-article'
}
</script>