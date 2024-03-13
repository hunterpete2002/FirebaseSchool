This requires a file in firebase folder called Config.js. This file should have your api keys and other relevant information to connect to firebase. I have also imported the firebase modules here.

Here is the import if needed:
import { getFirestore, collection, addDoc, serverTimestamp, QuerySnapshot, onSnapshot, query, orderBy} from "firebase/firestore"

And all possible neede information:

const firestore = getFirestore()
const MESSAGES = 'messages';

export {
    firestore,
    collection,
    addDoc,
    serverTimestamp,
    QuerySnapshot, 
    onSnapshot,
    MESSAGES,
    query,
    orderBy
};
